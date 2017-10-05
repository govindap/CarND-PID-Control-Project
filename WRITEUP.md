# CarND-Controls-PID Project Reflection
Self-Driving Car Engineer Nanodegree Program 

---
## 1. Student describes the effect of the P, I, D component of the PID algorithm in their implementation. Is it what you expected?
Visual aids are encouraged, i.e. record of a small video of the car in the simulator and describe what each component is set to.

Term P stands for Proportional and it takes current value of error(cte) and multiplies it by proportional gain Kp which is a tuning parameter.

Term I accounts for sum of past values of cte error and integral gain Ki is applied and added to the overall correction. 

Term D accounts for derivative of the slope of the error over time and derivative gain Kd is applied for the correction

## 2. Student discusses how they chose the final hyperparameters (P, I, D coefficients). This could be have been done through manual tuning, twiddle, SGD, or something else, or a combination!

- Low Ki and Kp helped keep the car within the track
- High Kd helped with smoothing the actuations




