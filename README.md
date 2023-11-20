# Portfolio

Organized and dependable candidate successful at managing multiple priorities with a positive attitude. 

Desperately waiting to gain hands-on experience to combine tireless hunger for new skills with desire to exploit cutting-edge data science technology. 

Willingness to take on additional responsibilities to meet the team and company goals. 

## Technical Skills

Operating System: **Windows**
Software/Tools: `Visual Studio Code`, `Power BI`, `Excel`, `Git`
Database/Server: `MySQL`, `PostgreSQL`
Programming Languages: `C`, `C++`, `Python`, `SQL`, `HTML`, `CSS`
Frameworks: `Django`, `Streamlit`
Python Libraries: `Pandas`, `Matplotlib`, `Plotly`, `Seaborn`, `Numpy`, `Scikit-Learn`, `Keras`, `TensorFlow`, `NLTK`, `BeautifulSoup`

## Projects
### [**- Streamlit Exploratory Data Analysis App**](https://chandu-2122-streamlit-eda-app-main-ehhr37.streamlit.app/)

 A one-line Exploratory Data Analysis (EDA) experience in a consistent and fast solution using ydata-profiling and Streamlit allowing users to conduct comprehensive EDA effortlessly.
 **Working**: This app analyzes the uploaded CSV files, providing in-depth insights into the dataset's characteristics through exploratory data analysis techniques.
 **Features**: 1. Upload CSV: Allows users to upload their CSV files for analysis.
 2. Profiling Report: Generates an exploratory data analysis report using ydata_profiling.
 3. Example Dataset: Offers the option to explore an example dataset in the absence of an uploaded CSV file.
 **Libraries Used**:
 1. `numpy` : used for various numerical operations, especially in generating example datasets or handling numerical data within the analysis.
 2. `pandas` : used to read and manipulate CSV files, organize data into DataFrames, and facilitates data exploration and presentation.
 3. `streamlit` : used as the primary framework for building the EDA web application, allowing easy integration of data visualizations, user inputs, and data analysis tools.
 4. `ydata_profiling` : Used to create comprehensive and interactive exploratory data analysis reports based on the uploaded or example datasets, providing detailed insights into the data's characteristics.
 5. `streamlit_pandas_profiling` : Facilitates the direct embedding of Pandas Profiling reports generated by ydata_profiling into the Streamlit app, allowing users to visualize and interact with the analysis within the app interface.
**App Snippet**:
 ![streamlit_eda](/assets/streamlit_eda.png)

 **Result**: Based on the uploaded CSV file or the example dataset, the EDA report is generated with the help of ydata-profiling and Streamlit on this app.
 **Conclusion**: Streamlit framework made easy to build web application for machine learning by simplifying the creation of interactive and data-driven apps.

### [**- Exploratory Data Analysis (EDA) on Rural Telangana Illiteracy Rates**](https://github.com/Chandu-2122/Power_BI)

 **Objective**: Analyse the number of illiterates in Telangana during the year 2014 and compare it with the current year(2023).
 **Data Source**: The dataset is taken from [Open Data Telangana](https://data.telangana.gov.in/dataset/number-illiterates-rural-telangana)
 **Dataset Description**: The dataset provides information about the number of illiterates in the rural areas of Telangana State by gender to gram panchayat level. This data is according to the old districts during the perioid 2014.
 **Visualizations**:
 `Mahabubnagar district`
 ![Rural_Mahabubnagar_1](/assets/r1m.png)

 `Karimnagar district`
 ![Rural_Karimnagar_2](/assets/rk2.png)
 
 `Rangareddy district`
 ![Urban_Rangareddy_1](/assets/ur1.png)
 
 `Warangal district`
 ![Urban_Warangal_2](/assets/uw2.png)
 
 **Insights Gained**:
 - During the period 2014, the top 3 highest number of illiterates according to the old districts were in Rural Telangana from Mahabubnagar with 14,75,524 members, Karimnagar with 10,58,837 members and Nalgonda with 10,45,305 members.
 - And in Urban Telangana the top 3 highest number of illiterates were from Rangareddy with 5,10,184 members, Warangal with 1,85,698 members and Karimnagar with 1,67,189 members.
 - The number of female illiterates was more than the male and transgender in Telangana.
 -  In Rural Telangana, Mahabubnagar district had 17% of illiterates of which maximum number of illiterates(6240) were from Makthal GP, and least(1) were in Rallacheruvu Thanda GP.
 -  In Urban Telangana, Rangareddy district had 34% of illiterates of which maximum number of illiterates(19126) were from Serilingampally Muncipality, and least(19) were in Ibrahimpatnam Muncipality.
 -  According to [indiacensus.net](https://www.indiacensus.net/states/telangana/literacy), the top 3 highest illiterate districts of Telangana in the year 2023 are Jogulamba Gadwal(former Mahabubnagar), Narayanpet(former Mahabubnagar) and Nagarkurnool(former Mahabubnagar).
 **Result**:
 ![Dashboard](/assets/powerbi_snippet.png)
 
 Conducted in-depth analysis of the illiteracy rates in rural Telangana using data sourced from Open Data Telangana and analyzed the number of illiterates in 2014 and compared these statistics with the current year (2023) to gauge changes and trends in literacy rates over the years.
 **Conclusion**:
 Even after 9 years, the district that was once known as Mahabubnagar has the highest percentage of illiterates in Telangana.

### [**- Web Scraping and Data Extraction from Amazon.in for Electronic Gadgets**](https://github.com/Chandu-2122/Web_Scrapping)

 Collected comprehensive data on electronic gadgets commonly used by software employees or students, such as laptops, tablets, smartphones, smartwatches, headphones, earphones, and earbuds. The focus was to extract this data during the Diwali season, especially emphasizing offer deals.
 **Data Source**: The data is scrapped from 'amazon.in' website.
 **Dataset Description**: Our required data from the webpage:
 - `name`: Title of the product
 - `brand`: Brand of the product
 - `model_name`: Model name of the product
 - `screen_size`: Display size of the screen
 - `colour`: Colour of the product
 - `cpu_model`: CPU model of the product
 - `ram_memory_installed_size`: Installed size of ram memory in the product
 - `operating_system`: Operating System of the product
 - `mrp`: Actual price of the product
 - `offer`: Offer on the product
 - `number_of_purchase_in_last_month`: Number of purchases of the product in last month
 - `number_of_ratings`: Number of ratings received for the product
 - `rating`: Overall rating of the product
 **Data Preperation**:
 Required data was extracted from the webpage by finding the mentioned tags and if no such tag was found then that value is replaced with an empty string.
 Products having no title value were removed from the dataset and then saved as a csv file.
 **Libraries Used**:
 1. `requests` : Used for sending HTTP requests to websites to fetch the HTML content of web pages
 2. `BeautifulSoup (from bs4)` : Used for parsing the HTML content obtained using the 'requests' library
 3. `pandas` : Used to create the DataFrame to organize and structure the scraped data
 4. `numpy`: Used to replace null values
 **Result**: Was successfully able to web scrape the amazon.in data once before the header i used got blocked or restricted.
 **Data Snippet**
 ![Data](/assets/data_snippet.png)

 **Conclusion**: Got to know that the success of web scrapping depends on various factors:
 Headers: Many websites require a valid user-agent string which allows/blocks/restricts the reuests.
 Website Policies: Some websites like amazon are having strict anti-scraping policies that are preventing or limiting scraping attempts.
 Website Changes: As we are relying on specific HTML tags to web scrape the data, sometimes our code might not be able to find the required HTML elements if the website changes its structure.
 
