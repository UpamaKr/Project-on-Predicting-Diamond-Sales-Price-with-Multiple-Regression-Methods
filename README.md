# About the Dataset

This dataset contains various characteristics of diamonds. Here is a brief rundown of the columns:

- `cut`: Refers to one of the most common diamond cuts. This dataset includes an additional cut called the 'Cushion Modified'.
- `color`: Clear diamonds are graded D-Z. The higher letters are more yellowish but are often better values since color is hard to determine once in a ring.
- `clarity`: Refers to the inclusions (i.e., internal flaws) in the diamonds seen through a jeweler's loupe or microscope. Fewer and smaller inclusions are better.
- `carat_weight`: Refers to the mass of the diamond. It's loosely connected with the dimension of a diamond but cut and cut_quality tend to play an equally large if not larger role.
- `cut_quality`: Refers to the GIA Cut Grading System which was developed in 2005 and is the de facto standard.
- `lab`: Is the grading lab. The big three are GIA, IGI, and HRD. Each diamond gets a lab certificate.
- `polish` and `symmetry`: Are what you would expect.
- `eye-clean`: Refers to whether the blemishes or inclusions can be seen with the naked eye. There are 10 grades.
- `culet_size`: Is the size of the circle you'd see if you looked straight down. None is ideal because it affects the amount of light that gets reflected.
- `culet_condition`: Indicates if the culet has any chipping, which is why some diamonds don't close to a point but rather have a very small flat spot.
- `fancy_color_` columns: Have to do with colored diamonds. Formerly, extremely rare but now common, popular, and almost always lab-grown.
- `fluor` columns: Refer to the effect of long-wave UV light. According to GIA, 25-35% have it; for ~10% of those, it's noticeable to an expert.
- `depth_percent` and `table_percent`: Are the relative measurements of the flat part of the top and the depth. This varies somewhat by cut.
- `meas_length`, `meas_width`, `meas_depth`: Are the absolute measurements of the stone.
- `girdle min/max`: Are where the ID of a stone is engraved. They also are where the stone meets the setting and play a role in reflection. There are 9 values ranging from extremely thin to extremely thick.
- `fancy` columns: Refer to colored diamonds. They can be natural like the extremely rare blue diamonds, or lab-grown. The columns refer to the colors, secondary colors, and their intensity.
- `total_sales_price`: Is priced in dollars.
