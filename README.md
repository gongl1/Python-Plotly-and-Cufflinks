# Python-Plotly-and-Cufflinks

Install plotly and cufflinks to call plots directly off of a pandas dataframe. These libraries are not currently available through conda but are available through pip. Install the libraries at command line/terminal using:

pip install plotly

pip install cufflinks

# Using Cufflinks and iplot()

scatter

bar

box

spread

ratio

heatmap

surface

histogram

bubble


# 3d Surface

df3 = pd.DataFrame({'x':[1,2,3,4,5],'y':[10,20,30,20,10],'z':[5,4,3,2,1]})

df3.iplot(kind='surface',colorscale='rdylbu')
