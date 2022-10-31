# R_visualization_basic

Here I am using Palmerpenguins 🐧 dataset from Rstudio.<br/>
The penguins dataset contains size measurements for three penguin species (Adelie, Chinstrap, and Gentoo) that live on the Palmer Archipelago in Antarctica.

### colnames(penguins) ⬇︎
![image](https://user-images.githubusercontent.com/90775147/198989925-5bdb1c7f-8479-45f5-9228-50e67a12f775.png)


### glimpse(penguins) ⬇︎
![image](https://user-images.githubusercontent.com/90775147/198989718-45a102e8-59f5-4bc0-943a-0d20fb657bee.png)


### head(penguins) looks like this ⬇︎
![image](https://user-images.githubusercontent.com/90775147/198989539-669cc423-ddff-46cd-a255-c1cc0bebd155.png)

### Create a plot in ggplot2

### ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))

The **ggplot()** function creates a coordinate system that you can add layers to.<br/>
The **geom_point()** function uses points to create scatterplots.

Here's the plot ⬇︎<br/>
![image](https://user-images.githubusercontent.com/90775147/198990825-35481b8e-ae73-4d28-9106-b93fd501a7ca.png)


