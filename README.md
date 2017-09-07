# IDL-example

p = polarplot(fltarr(3600)+(findgen(3600) mod 2), findgen(3600)/10*!DTOR, VERT_COLORS=bytscl(findgen(3600)), RGB_TABLE=1, AXIS_STYLE=0, DIMENSIONS=[256,256], /NO_TOOLBAR)
