# Multi Vehicle routing solution

![Logo](https://i.imgur.com/31MpZyG.jpg)

A simple solution to get dynamically optimize routes for multiple vehicles visiting a set of locations given real-life constraints such as limited capacity in a vehicle or delivery time windows. Just upload a pre-formatted route_request excel file with the details of transport orders and fleet of vehicles. You can easily configure costs to optimize the route plans for which is then sent to HERE API. The API will solve the multi-vehicle routing problem and provide the optimal sequence of locations according to the costs.

#### Solving sustainability issues
With the chaos of improper route management system and internal logistics, excessive fuel costs and consumption of energy is on rise and with every consumption there is a hidden cost of carbon emission being involved for the globe. To optimize this we came up with the solution which can help transport services to better function given the limited amount of delivery time and route optimization.

![WebApp](https://i.imgur.com/5RX2ROo.png)


#### Prerequisites
- Python3
- Streamlit

#### Installation
1. Get the API key from [HERE developer portal](https://developer.here.com/) and for [OpenrouteService](https://openrouteservice.org/)
2. Install dependencies
`pip install -r requirements.txt`
3. Run the app on streamlit
`streamlit run app.py`
