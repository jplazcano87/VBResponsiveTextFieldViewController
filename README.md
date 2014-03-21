VBResponsiveTextField
=====================

A UIViewController subclass that won't let UITextFields be hidden by the keyboard.

Usage
-----

Subclass the VBResponsiveTextViewController for a view controller that will move it's top level view around so that the actively edited UITextField is never hidden underneath the keyboard input. Simple as that.

N.B.
----

The VBResponsiveTextFieldViewController class conforms to the UITextField delegate protocol, so make sure any UITextFields in your view set their delegate property to the instance of the class.

The distance between the keyboard and the active UITextField is defined by the 'kPreferredTextFieldToKeyboardOffset' macro in VBResponsiveTextFieldViewController.h