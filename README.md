# popup-complete

Packaging [these code snippets](http://www.emacswiki.org/emacs/PopUp) by created LinhDang.

## Screenshot

![popup-complete](image/popup-complete.png)


## Requirements

- [popup-el](https://github.com/auto-complete/popup-el/)


## Customization

#### `popup-complete-enable`(Default is `t`)

Use popup completion if this variable is non-nil.

#### `popup-complete-enabled-modes`(Default is `nil`)

Major modes which enables `popup-complete`


## Sample Configuration

```lisp
;; Enables only 'lisp-interaction-mode' 'ruby-mode' 'scala-mode'
(custom-set-variables
 '(popup-complete-enabled-modes '(lisp-interaction-mode ruby-mode scala-mode)))
```
