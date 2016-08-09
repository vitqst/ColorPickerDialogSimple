# ColorPickerDialogSimple

step 1 : copy 2 file to your project 

step 2 : using 
```java
ColorPickerDialog colorPickerDialog = new ColorPickerDialog(DrawActivity.this, currentColor, new ColorPickerDialog.OnColorSelectedListener() {
					@Override
					public void onColorSelected(int color) {
						// your code 
					}
				}) ;
				colorPickerDialog.show();
```
