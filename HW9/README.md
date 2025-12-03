I worked alone in this assignment as were the instructions.

Old Plot:

<img width="1493" height="1329" alt="image" src="https://github.com/user-attachments/assets/b7b0cc39-6210-4300-ad3b-c2321be09ccd" />


Notebook Plot (from HW 5/6):

<img width="1343" height="1251" alt="image" src="https://github.com/user-attachments/assets/cb81c8db-ab68-43e9-bdd9-294d9dcc54cd" />

Updated the log time plot from the GRB MCMC notebook, which is the second plot in the notebook. I added gridlines to make the data a little easier to visualize the values of. I changed the colors to a color-blind friendly palette, as there used to be green and red plotted on top of one another especially which was bad. I also added a title and scaled down the size of the data points, as they were quite large and overcrowded the space near the top left. I tried to fix the clumping of the data points as well, but had no such luck.

Note: Title should state GRB, not supernova

Bad Plot (https://arxiv.org/pdf/physics/0601001):

<img width="565" height="387" alt="image" src="https://github.com/user-attachments/assets/abf463b8-d740-4e6d-92d0-73e8bd7b48f7" />

The issue with this plot is that it tries to do many things in one plot. The plot is showing the Rayleigh scattering as a function of energy, which has an issue with the y-axis being too condensed together. But then the authors also overlay the schematic of the experiment on top of the plot. They are showing a plot of data and a schematic of the experiment in the same space. I would break them apart into two seperate pieces, to avoid unnecessary clutter.

Good Plot (https://arxiv.org/pdf/2010.12279):

<img width="1148" height="631" alt="image" src="https://github.com/user-attachments/assets/aa483879-9c65-439a-a29f-66eb9b005a43" />

While I initially said this was a bad plot, I realized that was more because it was complicated to understand and first and not because its actually bad. What it does right is have good color contrast between sections, indicating what experiment the data is from, which is also mentioned in the legend. The colors are also colorblind friendly, which is great for accessibility. The graph includes error bars in with the data, which further improve information gained from each the data. The biggest change I would add would maybe be the year of the different experiments, to show how the data has moved over time, but that would only be needed for people who do not already understand the data (which is a little tricky to explain).


Reference Color Palette from Notebook Graph:

<img width="738" height="962" alt="image" src="https://github.com/user-attachments/assets/30a73ed8-0be7-41b6-8043-1d4e092a6a05" />
