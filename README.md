Our controller is an improvement of the fixed time-gap model. Our controller not only considers the relative speed between the two vehicles but also takes into account the relative speed and acceleration. As a result, the ego car's speed is smoother than in the basic model, and when the lead car has a significant acceleration, the ego car also accelerates more strongly.

When using our controller in simulations, we should observe that the ego car's speed remains relatively smooth. When the lead car starts moving, the ego car will quickly increase its acceleration. However, if the lead car is only fluctuating around a certain speed, the ego car's speed change is not drastic.

This model performs well when there is a large speed difference between the two cars or when the lead car has high acceleration. However, at low speeds, the two cars may be too close, as this is a model based on a fixed time gap. We plan to address this issue in the next version.
