# predictive_modeling
read csv files using pandas.
You can start with whichever you prefer.
What I will need in the end is a pandas dataframe with the following columns(in no particular order):
   - machine_id
   - date_time
   - model 
   - age
   - voltage
   - rotate
   - pressure
   - vibration
   - error 1
   .
   .
   - error 5
   - comp1_fail
   .
   .
   - comp4_fail
   - comp1_maint
   .
   .
   - comp4_maint


UPDATE as of 3/21/2024
from MICHAEL - I uploaded the final data frame comprised of the columns that you asked for. 
               I also uploaded the code I used to transform the data sets into one.
               I used Google colab to run the code, you may need to edit the directories if you want to use the code yourself as I just uploaded the csv files directly to the notebook.



# test the model
print(compute_failure_probability(93,0))
print(compute_failure_probability(93,1))
print(compute_failure_probability(93,2))
print(compute_failure_probability(93,3))
print(compute_failure_probability(80,0))

   
71/71 [==============================] - 5s 11ms/step
0.00012981757890884182
71/71 [==============================] - 1s 9ms/step
0.0004923086180497194
71/71 [==============================] - 1s 9ms/step
0.0020386190954013728
71/71 [==============================] - 1s 8ms/step
44.84091103076935
71/71 [==============================] - 1s 8ms/step
0.021167252270970494
