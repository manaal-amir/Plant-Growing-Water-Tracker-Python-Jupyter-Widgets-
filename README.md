## Plant Growing Water Tracker (Python, Jupyter Widgets)  
### Overview  
This interactive Plant Growing Water Tracker helps you visualize your daily watering habit as the growth of a virtual plant. Each time you “water the plant” by clicking the button, your plant grows a little bit, encouraging you to stay hydrated and take care of your plant!  

### Features  
Set a daily watering goal (default is 8 times).  

Click “💧 Water the Plant!” to water your plant and grow it.  

Visual progress bar made with plant emojis 🌱 shows your plant’s growth.  

Motivational messages reflect the plant’s growth stages from seed to full bloom.  

Reset button to start over and grow a new plant.  

## How It Works  
Uses ipywidgets to create interactive buttons and output display within Jupyter notebooks.  

The watering button increases the watering count and updates the plant growth progress.  

The progress bar visually fills with 🌱 emojis as you water.  

Messages change depending on the stage of plant growth.  

The reset button clears the progress so you can start fresh.  

## Code Breakdown  
DAILY_GOAL: Number of times you want to water your plant each day.  

water_given: Tracks how many times the plant has been watered.  

Buttons for watering the plant and resetting the tracker.  

get_progress_bar(current, total): Generates a progress bar made of 🌱 emojis representing plant growth.  

update_display(): Updates the output with the current progress and messages.  

water_plant(b): Increases watering count and updates display when the water button is clicked.  

reset_plant(b): Resets the watering count and display.  

display(): Shows the buttons and progress in the notebook interface. 

## Output Screenshots  
![image](https://github.com/user-attachments/assets/6a6c98df-0220-428b-94d5-3a0020606350)  
![image](https://github.com/user-attachments/assets/dbee7503-c49c-4a2e-9326-57cc70df316c)  
![image](https://github.com/user-attachments/assets/2de61c9e-318e-4476-b918-e4097fc400bc)  




## License  
This project is open-source and free to use.

