### Converting the wkt format file into shape file
## Note: Steps may vary as per the user's need.
1. Decompress the file(s) (any/all required state.csv.xz file(s)). 
2. Open your workspace(in my case, I did it in QGIS).
3. Select **Layer -> Add Layer -> Add Delimited Text Layer...** from the menu toolbar, the decompressed file that you'd got must be in csv format.
   ![](/images/1.jpg)
4. Browse the desired csv file, under **File Format** section, select **Custom delimiters** and then select **Tab** and **Comma** checkboxes (these options will work for most of the geometery shapes: points, polygons, etc.). 
   ![](/images/2.jpg)
> After selecting the checkboxes, users are advised to tally the changes made in Sample data view. 
5. Under **Geometery Definition**, select the options accordingly (refer attached image, also do mind the **Geometery CRS** dropdown).
   ![](/images/3.jpg)
> In my case, the geometery type is multipolygons and the datapoints represent the boundaries of villages.
6. Additional step: You may crosscheck your work by adding the **Point** shape distribution file of the same csv.
7. Hidden step: Instead of selecting **Custom Delimiters** in step 4, you can simply use the **CSV** option as well (hehehe).

