IL_EX
=====

Some additional functions for AHK ImageList controls:

- `IL_EX_Copy(ILID, From, To)`  
Copies images within this image list.
- `IL_EX_Draw(ILID, Index, HWND[, X := 0[, Y := 0[, Styles := 0x00]]])`  
Draws an image list item in the specified control's device context.
- `IL_EX_Duplicate(ILID)`  
Creates a duplicate of an existing image list.
- `IL_EX_GetHICON(ILID, Index[, Styles := 0x00])`  
Creates an icon from an image in an image list.
- `IL_EX_GetImageCount(ILID)`  
Retrieves the number of images in an image list.
- `IL_EX_GetSize(ILID, W, H)`  
Retrieves the dimensions of images in an image list.
- `IL_EX_Remove(ILID, Index)`  
Removes an image from an image list.
- `IL_EX_Replace(ILID, Index, HBITMAP[, HMASK := 0])`  
Replaces an image in an image list with a new image.
- `IL_EX_ReplaceIcon(ILID, Index, HICON)`  
Replaces an image with an icon or cursor.
- `IL_EX_SetBkColor(ILID[, BkColor := 0xFFFFFF])`  
Sets the background color for an image list.
- `IL_EX_SetImageCount(ILID, NewCount)`  
Resizes an existing image list.
- `IL_EX_SetSize(ILID, W, H)`  
Sets the dimensions of images in an image list and removes all images from the list.
