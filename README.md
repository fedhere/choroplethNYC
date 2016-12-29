# choroplathNYC
A function to make a choroplath of NYC from a shapefile data. The colorbar location is tuned to the shape of NYC (although it can be modified) and enabled both continuous and discrete color bars.


You can call it as :
    '''
    f, ax, cb = cp.choroplethNYC(gdf, "column_name", kind='continuous', cmap="viridis")
    '''
with gdf a geopandas GeoDataFrame, with a valid geometry column, and with column_name a valid column name within the geo data frame (numerical or that can be converted to numerical).


