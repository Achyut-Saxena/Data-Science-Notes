# 🧹What is Data Cleaning/ Data Wrangling/ Data Pre-Processing?🧹
The process of converting or mapping data from initial "raw" format into another format, in order to prepare the data for further analysis.

While going through Data Cleaning process we might encounter **Missing Values!**
### Missing Value (What to do with it?)😢
- Check withing the data collection
- Drop the missing value
	- drop variable
	- drop daata entry
- Replace the missing value
	- replace with an avg. val of column
	- replace with frequency
	- replace based on other functions
- Leave it as missing data

### Data Formatting 📝:
Bringing data into a common standard of expression allows users to make meaningful comparison.

### Data Normalization ⚖️:
- Simple Feature scaling: range 0-1
$$x_{new} = \frac{x_{old}}{x_{max}}$$
- Min-Max: range 0-1
$$x_{new} = \frac{x_{old}-x_{min}}{x_{max}-x{min}}$$
- Z-score: range -3 to +3
$$x_{new} =  \frac{x_{old}-x_{min}}{x_{max}-x_{min}}$$

### Binning 🗄️:
- Grouping of values into "bins"
- Converts numeric into categorical variables

_One Hot Encoding : method of converting data to prepare it for an algorithm and get a better prediction._
