# HAL Robotics Framework (β)
HAL Robotics Framework beta release and associated documentation. This is also the repository for filing bug reports for the HAL Robotics Framework Beta releases.

### Access
Please follow the instructions on our [website](https://hal-robotics.com/getstarted/) to get the HAL Robotics Framework (β).

# Improvements and Bug Reports
We are going to continue our internal testing of all our software and will be releasing fixes as quickly as we can but we also need your help to stabilize the framework.
The best way for us to correct issues is to be able to reproduce them ourselves and delve into the code to see what’s going wrong.
Therefore we ask tht you please refer to the [Contribution guideline](https://github.com/HALRobotics/Beta/blob/master/CONTRIBUTING.md) before submitting bug reports or enhancement requests.

The more feedback you give, the more errors you find, the more issues you report, the faster we can get the HAL Robotics Framework to a stable release and, more importantly, the more influence you will have over the final product so it does exactly what you want in the way you want.

## Common Issues 
[Compatibility between plugins](https://github.com/HALRobotics/Beta/issues/22)

[Grasshopper loading errors](https://github.com/HALRobotics/Beta/issues/69)

[more...](https://github.com/HALRobotics/Beta/issues?q=is%3Aissue+label%3A%22common+issue%22)

## Update Requirements
### 1.x -> 1.3
1. The **Attach** component has been rewritten in such a way that the auto-updater cannot update the component for you. Please replace the **Attach** component if it is marked as _Old_.
2. The **Upload** component has been rewritten in such a way that the auto-updater cannot update the component for you. Please replace the **Upload** component if it is marked as _Old_.
3. The **Controller** component has new functionality within the _Configurator_. The component itself will not be marked as _Old_ but if you notice that the _Configuration_ isn't saved within the **Controller** component, please replace the component.
