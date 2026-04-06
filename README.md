# Predictive-Pro-Hubs-Using-SARIMAX
Predictive Pro-Hubs: Using SARIMAX and Inventory Simulation to Optimize LTL Flooring Distribution. Modeled flooring demand via SARIMAX, then simulated 10-pallet vs. 3-pallet LTL Hubs to optimize 98% Service Levels &amp; 50% Truck Utilization for builders.
<img width="847" height="468" alt="image" src="https://github.com/user-attachments/assets/2b42c4db-1f3c-4a22-913b-b8bccaf81a29" /> <br>
This simple bar chart demonstrates the consistency delievered by a simulated flooring manufacturer with high-SL-penality contracts with multiple home builders. Using a Pro-Hub system, the company is able to utilize small footprint holding facilities that feature show-rooms and storage for builders to conveniently pick up their materials. This Pro-Hub system enables a hybrid Just-in-Time manufacturing system while keeping the high-service level requirements for local home building contracts.

# Finished Product #
To see the finished Kaggle Notebook, [Click Here!](https://www.kaggle.com/code/marissan/predictive-pro-hubs-items-135-and-stores-248)

**Delieverables** <br> 
- An simulated system and ordering frequency that prioritizes high service levels and full-pallet shipment requirements.

# Programs #
- Python
- Copilot/Gemini
    - Used as learning aids w/ code debug, proper process structure, and exploration

# Goals #
Hello! Today we are using the SARIMA model developed in [this notebook](https://www.kaggle.com/code/marissan/store-1-item-1-forecasting-sarima-v-prophet) and used to forecast 1 item's inventory in [this notebook](https://www.kaggle.com/code/marissan/the-98-strategy-lean-inventory-simulation-s1-i1) to forecast 3 different stores and 3 different items. Once we do that, we'll continuously add more realistic variables such as pallet sizes/constraints, truck capacity, and a high-penalty service level requirement.

<br>

**The goal is a 98% service level!**

# Data Source Info #
In this case, I chose the [Store Item Demand Challenge dataset](https://www.kaggle.com/competitions/demand-forecasting-kernels-only) from 8 years ago as it's supposed to be friendly for beginners and is already clean! 

# Opportunities #
By the end of the project, I could have explored adding in more SKUs to accomodate an ideal 10 pallet trailer load. Additionally, I could've add more realistic constraints like item weights, warehouse capacity, and stricter inventory on hand requirements. 

# Reflection #
I struggled with this one a little! Juggling 3 items and 3 stores was a challenge, and deciding what direction to take the project once I did that made everything 9x harder. It was one of those projects where going back and adding anything would be a bit of a hassle. I think struggle is good practice though (thats why some code blocks are commented to all hell, I gotta take notes somewhere!), and I hope to continue building skills and understanding of Python concepts to keep filling out my inventory and supply chain tool kits. Thanks for reading!

