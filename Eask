;; -*- mode: eask; lexical-binding: t -*-

(package "echo-bar"
         "1.0.0"
         "Turn the echo area into a custom status bar")

(website-url "https://github.com/elp-revive/echo-bar.el")
(keywords "convenience" "tools")

(package-file "echo-bar.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source 'gnu)

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432

(add-hook 'eask-before-compile-hook
           (lambda ()
             (setq byte-compile-error-on-warn t)))

