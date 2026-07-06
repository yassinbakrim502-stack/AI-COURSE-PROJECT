# AI-COURSE-PROJECT

## Summary
This is the final project submission for the Artificial Intelligence Course. 
The project includes all required code and files.
def main():
    # Quick simulation showing how we match crops to soil data
    soil_data = {'nitrogen': 45, 'phosphorus': 50, 'potassium': 42, 'ph': 6.5, 'rainfall_mm': 120, 'humidity_pct': 75}
    prediction_scores = [0.91, 0.45, 0.78, 0.88] 
    crop_options = ['Tomatoes', 'Potatoes', 'Cotton','Soyabeans']
    
    print("--- Crop Match Results ---")
    for i in range(len(crop_options)):
        print("%s Match Score: %.1f%%" % (crop_options[i], prediction_scores[i] * 100.0))

main()
