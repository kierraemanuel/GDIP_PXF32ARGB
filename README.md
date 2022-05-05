# GDIP_PXF32ARGB
iHeight = _GDIPlus_ImageGetHeight($hImage) $Reslt = _GDIPlus_BitmapLockBits($hImage, 0, 0, $iWidth, $iHeight, $GDIP_ILMREAD, $GDIP_PXF32ARGB) $Scan0 = DllStructGetData($Reslt, "Scan0")
