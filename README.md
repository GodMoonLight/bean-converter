# bean-converter
a plugin for IDEA, which generate code convert a java bean to another bean


### Usage:
#### Converter method

1. Put the caret in any place within the class, press **Alt+Ins** or **Command + n**.
2. select **Converter method** in menu or use the shortcut **Ctrl+Alt+G**.
3.In the dialog select the Class you want to convert <b>To</b> and select the class you want to convert **From**.
4. Press **Ok** and converter method will be added to your current class.
5. Plugin also writes in comments list of fields, that were not mapped (appropriate setter or getter is missing or different types).


#### Converter to method
1. Put the caret in any place within the class, press **Alt+Ins** or **Command + n**.
2. select **Converter to method** in menu.
3. In the dialog select the Class you want to convert **To**.
4. Press **Ok** and converter method will be added to your current class.
5. Plugin also writes in comments list of fields, that were not mapped (appropriate setter or getter is missing or different types).


#### Converter from method
1. Put the caret in any place within the class, press **Alt+Ins** or **Command + n**
2. select **Converter from method** in menu.
3. In the dialog select the Class you want to convert **From**.
4. Press **Ok** and converter method will be added to your current class.
5. Plugin also writes in comments list of fields, that were not mapped (appropriate setter or getter is missing or different types).
