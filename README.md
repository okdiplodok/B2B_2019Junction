This dashboard designed to monitor profiles of people visiting Finnish national parks and do crowd control is my contribution to the Junction 2019 hackathon. Our team joined the Sustainability track. We worked on the challenge which was aimed to help National parks of Finland to create a more sustainable and nature-friendly experience for its visitors. The challenge description can be found [here](https://2019.hackjunction.com/challenges/finding-ways-to-keep-finlands-national-parks-enjoyable-for-both-foreign-travels-and-locals). Our team has one the 2nd place on the Sustainability track, yay! :tada:

This template was borrowed from the Dash collection of templates. In the text below there is the original documentation. 

# Dash Natural Gas Well Production

This is a demo of the Dash interactive Python framework developed by [Plotly](https://plot.ly/).

Dash abstracts away all of the technologies and protocols required to build an interactive web-based application and is a simple and effective way to bind a user interface around your Python code. To learn more check out our [documentation](https://plot.ly/dash).

## Getting Started

### Running the app locally

First create a virtual environment with conda or venv inside a temp folder, then activate it.

```
virtualenv venv

# Windows
venv\Scripts\activate
# Or Linux
source venv/bin/activate

```

Clone the git repo, then install the requirements with pip

```

git clone https://github.com/plotly/dash-sample-apps
cd dash-sample-apps/apps/dash-oil-and-gas
pip install -r requirements.txt

```

Run the app

```

python app.py

```

## About the app

This Dash app displays oil production in western New York. There are filters at the top of the app to update the graphs below. By selecting or hovering over data in one plot will update the other plots ('cross-filtering').

## Built With

- [Dash](https://dash.plot.ly/) - Main server and interactive components
- [Plotly Python](https://plot.ly/python/) - Used to create the interactive plots


