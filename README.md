# Fifa21
It's a project to showcase data cleaning, transforming and visualization techniques, dataset pulled from Kaggle
Some of the ideas and inspirations are, what are the top 10 players of the world, what info can I get from them, i.e. their wage, BP, nationality, names, values, etc.


https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring



And because of some of the libraries don't allow the visualization on GitHub you can use this link to be able to see all the graphs in a proper fashion:


https://nbviewer.org


https://github.com/IvanH29/Fifa21/blob/main/Fifa%2021%20data.ipynb


fifa_dictionary = {
    
    "Nationality": "Nationality of the player",
    
    "Positions": "Positions in which the player can play",
    
    "Name": "Name of the player",
    
    "Age": "Age of the player",
    
    "↓OVA": "Overall rating of the player",
    
    "POT": "Potential rating of the player",
    
    "Height": "Height of the player (in centimeters)",
    
    "Weight": "Weight of the player (in kilograms)",
    
    "foot": "Dominant foot of the player (left or right)",
    
    "BOV": "Base value of the player",
    
    "BP": "Best Position of the player",
    
    "Growth": "Potential growth of the player",
    
    "Joined": "Year the player joined the current team",
    
    "Value": "Value of the player",
    
    "Wage": "Wage of the player",
    
    "Attacking": "Attacking attributes of the player",
    
    "Crossing": "Crossing accuracy",
    
    "Finishing": "Finishing accuracy",
    
    "Heading Accuracy": "Heading accuracy",
    
    "Short Passing": "Short passing accuracy",
    
    "Volleys": "Volleys accuracy",
    
    "Skill": "Skill attributes of the player",
    
    "Dribbling": "Dribbling ability",
    
    "Curve": "Curving the ball in free-kicks",
    
    "FK Accuracy": "Free-kick accuracy",
    
    "Long Passing": "Long passing accuracy",
    
    "Ball Control": "Ball control ability",
    
    "Movement": "Movement attributes of the player",
    
    "Acceleration": "Acceleration",
    
    "Sprint Speed": "Sprint speed",
    
    "Agility": "Agility",
    
    "Reactions": "Reaction speed",
    
    "Balance": "Balance",
    
    "Power": "Physical power of the player",
    
    "Shot Power": "Shot power",
    
    "Jumping": "Jumping ability",
    
    "Stamina": "Physical endurance",
    
    "Strength": "Physical strength",
    
    "Long Shots": "Long shots accuracy",
    
    "Mentality": "Mentality attributes of the player",
    
    "Aggression": "Aggression",
    
    "Interceptions": "Interceptions of passes",
    
    "Positioning": "Positioning on the field",
    
    "Vision": "Vision for passing",
    
    "Penalties": "Penalties accuracy",
    
    "Composure": "Level of composure",
    
    "Defending": "Defensive attributes of the player",
    
    "Marking": "Marking ability",
    
    "Standing Tackle": "Standing tackle",
    
    "Sliding Tackle": "Sliding tackle",
    
    "Goalkeeping": "Goalkeeping attributes",
    
    "GK Diving": "Goalkeeper diving ability",
    
    "GK Handling": "Goalkeeper handling ability",
    
    "GK Kicking": "Goalkeeper kicking ability",
    
    "GK Positioning": "Goalkeeper positioning ability",
    
    "GK Reflexes": "Goalkeeper reflexes",
    
    "Total Stats": "Total statistics of the player",
    
    "Base Stats": "Base statistics of the player",
    
    "W/F": "Weak Foot rating of the player (1 to 5)",
    
    "SM": "Skill Moves rating of the player (1 to 5)",
    
    "A/W": "Attacking Work Rate (1 to 5)",
    
    "D/W": "Defensive Work Rate (1 to 5)",
    
    "IR": "Injury Resistance index",
    
    "Hits": "Player's popularity",
    
    "Team": "Team to which the player belongs",
    
    "Contract_Duration": "Duration of the player's contract"
    
    }
