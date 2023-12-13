# xarray-cartopy-rasterio-rioxarray-
"""tips:
1、！！！！！导入rasterio或者rioxarray一定要在导入cartopy之前，否则会报错{找不到指定的程序}
2、！！！！！使用xarray读取nc文件时，后续导入cartopy时,会报错{engein rasterio dll 找不到指定的程序}，解决方法是在导入cartopy之前，先导入rasterio或者rioxarray,导入的要求同上
"""
