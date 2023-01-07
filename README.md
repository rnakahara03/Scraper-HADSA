# Energy Consumption Scraper
Every month, the conservation coordinators at the UC Berkeley Housing and Dining Sustainability Advocates collate average electricity consumption metrics for over 30 campus dorms (representing 5000+ campus residents) from an interactive website maintained by the Residential & Student Services Program (https://engagementdashboard.com/universityofcaliforniaberkeley/rssp/building-performance).

The process is inefficient and only provides 12 data points to conduct annual analyses. We are re-launching the Cool Campus Challenge in spring 2023 to incentivize campus residents to reduce their water and energy footprints. By storing daily energy consumption values, we will be able see if the initiative reduced consumption by statistically significant margins. 

I used bs4 and selenium to scrape the dynamic website and extracted only the dorm name and actual energy consumption values. The data will be collated in a file called merged.csv on your local device. Although there are a few bugs in the code that I need to fix (and optimize efficiency), my long-term goal with this project is to connect the data to a graphical-user interface that enables any campus resident to plot their building's energy consumption during a chosen interval. I spearheaded this project in an attempt to hone my technical skills whilst improvind the efficiency of data collection in the long run.

## Amendments
Please follow the procedures on this website (https://chromedriver.chromium.org/downloads) to download a compatible version of chromedriver.

The following lines of code must be amended if you decide to run my script on your device:
- Replace the input for read_csv with the path on your device

## Resources
I would not have been able to implement this scraper and the associated statistical analysis had it not been for the following sources:

https://www.youtube.com/watch?v=RvCBzhhydNk&ab_channel=Pythonology

https://realpython.com/beautiful-soup-web-scraper-python/

https://towardsdatascience.com/how-to-easily-automate-your-python-scripts-on-mac-and-windows-459388c9cc94

https://realpython.com/linear-regression-in-python/#simple-linear-regression

I have adapted the code from these resources primarily and will continue to update this file as I make progress on the project. 
