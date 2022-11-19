# **The Challenge**

To predict the weight of an aircraft with its passengers, cargo and fuel, just before leaving the terminal at departure

## **The Dataset**

The train set contains over 765K flights from Ryanair in Europe between Nov 1st 2019 and
March 31st 2022. These have been sampled at random from the whole dataset received
from Ryanair. The test set contains the remaining flights on the same period, which amount
to ca. 191K flights.

The dataset contains 28 variables which we grouped in 4 different types:

- target variable
- variables known before prediction is made
- variables known after prediction is made
- estimations from Ryanair models

**Target variable**

The target variable is `TeledyneRampWeight` (actual weight on ramp before push back).
This is generally measured by sensors on the wheels once the flight is fully loaded and just
before the plane starts to taxi towards the take-off track.

### **Note**: Dataset is not uploaded due to NDA constraints
