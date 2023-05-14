## things i would like to know more about

### Matplotlib, Seaborn, and Bokeh are popular Python libraries used for data visualization, but they have different features and use cases.

- Matplotlib:

    Matplotlib is a powerful and flexible library for creating static, animated, and interactive visualizations in Python.
    It provides low-level control over individual plot elements and allows for customization.
    Matplotlib is a foundational library for other visualization libraries like Seaborn and Bokeh.
    Example: Matplotlib is suitable for creating basic line plots, scatter plots, bar plots, histograms, etc. For example, if you want to plot a simple line graph showing the trend of a stock price over time, Matplotlib can be a good choice.

- Seaborn:

    Seaborn is built on top of Matplotlib and provides a high-level interface for creating informative and visually appealing statistical graphics.
    It simplifies the process of creating complex visualizations by providing default settings and themes.
    Seaborn offers various plot types, including relational, categorical, and distribution plots.
    Example: Seaborn is well-suited for creating a box plot to visualize the distribution of a numerical variable across different categories. For instance, you can use Seaborn to plot a box plot showing the distribution of house prices across different neighborhoods in a city.

- Bokeh:

    Bokeh is a library specifically designed for creating interactive visualizations for modern web browsers.
    It focuses on providing interactive and dynamic plots that can handle large and streaming datasets.
    Bokeh allows for creating interactive tools like sliders, dropdowns, and zooming/panning capabilities.
    Example: Bokeh is suitable for creating interactive scatter plots with tooltips. For example, you can use Bokeh to plot a scatter plot of cities on a map, where each point represents a city, and hovering over a point shows additional information like city name, population, and temperature.

### In Seaborn, the main functions to create different types of plots are:

- Relational plots:

    sns.scatterplot(): Creates a scatter plot to show the relationship between two numerical variables.
    sns.lineplot(): Plots a line chart to show the relationship between two numerical variables, typically with one variable representing time.
    Example use case: Visualizing the correlation between a student's study hours and their exam scores using a scatter plot or line plot.
- Categorical plots:

    sns.barplot(): Displays the mean value of a numerical variable for different categories using vertical bars.
    sns.boxplot(): Shows the distribution of a numerical variable across different categories using quartiles and outliers.
    Example use case: Comparing the average sales of different products in a retail store using a bar plot or analyzing the distribution of customer ratings for different product categories using a box plot.

- Distribution plots:

    sns.histplot(): Creates a histogram to represent the distribution of a numerical variable.
    sns.kdeplot(): Plots a kernel density estimate to visualize the underlying distribution of a numerical variable.
    Example use case: Examining the distribution of heights in a population using a histogram or visualizing the probability density of exam scores using a kernel density plot.


### The Seaborn Cheat Sheet plays a valuable role in a Python developer's workflow by providing a concise and easily accessible reference guide for Seaborn functionalities. Here are some key sections and elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities:

- Plotting functions: The cheat sheet includes a section dedicated to the main plotting functions available in Seaborn. It provides a summary of each function's purpose and usage, making it easy to identify the appropriate function for a specific visualization task.

- Plot types: The cheat sheet showcases various plot types supported by Seaborn, such as scatter plots, line plots, bar plots, box plots, violin plots, and many more. Each plot type is briefly described, and the corresponding function name is provided, enabling developers to quickly identify the appropriate plot type for their data.

- Styling options: Seaborn offers several options for customizing the appearance of plots, such as color palettes, themes, and plot aesthetics. The cheat sheet includes sections dedicated to these styling options, providing a quick overview of available choices and their respective functions or parameters.

- Grids and axes control: Seaborn allows developers to control the layout and organization of subplots, grids, and axes. The cheat sheet provides information on functions and parameters related to these layout and control options, making it easier to create complex and multi-plot visualizations.

- Additional functionalities: Seaborn offers additional functionalities beyond basic plotting, such as statistical estimation, data transformations, and visualization enhancements. The cheat sheet includes sections highlighting these features, allowing developers to quickly discover and utilize them when needed.

- Code examples: The cheat sheet often includes concise code examples for each featured functionality. These examples demonstrate the basic usage of specific functions or plot types, serving as handy templates that developers can modify and adapt for their own data.

Overall, the Seaborn Cheat Sheet acts as a go-to resource that helps Python developers quickly reference Seaborn functionalities, understand their purpose, and efficiently implement them in their data visualization workflow.