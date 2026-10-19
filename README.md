# CARB-AI 

CARB-AI is an experimental AI project exploring how multimodal artificial intelligence can estimate the carbohydrate content of food using food images and natural-language descriptions.

The project investigates the potential of combining visual recognition, language understanding, and nutritional information to make food carbohydrate estimation more accessible.

Live prototype: https://carb-ai.netlify.app/

**Project Overview**

Estimating the carbohydrate content of a meal can be challenging because foods vary in portion size, ingredients, and preparation methods. CARB-AI explores how AI could help interpret food images and descriptions to produce an estimated carbohydrate value.

The project is an ongoing prototype intended for experimentation and learning, not a clinically validated medical application.

**Objectives**

Explore multimodal AI for interpreting food images and text descriptions.

Investigate methods for estimating carbohydrate content.

Identify factors that affect estimation accuracy, including portion size and hidden ingredients.

Explore ways to integrate food recognition, nutritional data, and calculations into a more self-contained AI agent.

Identify appropriate methods for evaluating the reliability of AI-generated estimates.

**Current Challenges**

**1.** Carbohydrate-estimation accuracy

Food recognition alone is not enough to determine the carbohydrate content of a meal. Accurate estimation may require information about:

Portion size and food weight.

Ingredients, sauces, and cooking methods.

The nutritional composition of the specific food.

Uncertainty in image interpretation and food identification.

An important next step is to evaluate the prototype against meals with known ingredients, measured portions, and independently established nutritional values.

**2.** Agent integration

Another area of exploration is building a more self-contained agent that can coordinate food recognition, portion clarification, nutritional data retrieval, and carbohydrate calculations.

The goal is to reduce unnecessary dependence on separate services while maintaining transparency, reliability, and the ability to identify uncertainty.

Potential Evaluation Approach

Future evaluation could investigate:

Absolute error: the difference between the estimated and reference carbohydrate values, measured in grams.

Food identification: how reliably the system identifies foods and ingredients.

Portion estimation: how much errors in portion size affect the final result.

Robustness: how performance changes across different foods, cuisines, lighting conditions, and meal presentations.

Uncertainty handling: whether the system recognises when it lacks enough information to provide a dependable estimate.

These are proposed evaluation directions, not claims of achieved performance.

**Safety and Limitations**

CARB-AI is an experimental educational project. Its carbohydrate estimates have not been clinically validated.

This prototype must not be used to determine insulin doses or guide real-world diabetes treatment. It is not a substitute for a qualified healthcare professional or an established diabetes-management plan.

Carbohydrate estimation and insulin-dose calculation are distinct tasks. Any future investigation involving insulin dosing would require appropriate clinical oversight, rigorous validation, and safeguards before any potential real-world use.

**Future Directions**

Improve food identification and portion estimation.

Investigate reliable nutritional data sources.

Develop a more integrated AI-agent workflow.

Evaluate estimation errors using a documented test dataset.

Explore methods for communicating uncertainty and requesting user corrections.

**About the Project**

CARB-AI is like an exploration of multimodal AI and its potential applications in healthcare.

Feedback, research paper recommendations, and suggestions for evaluation are welcome.

Status: Experimental prototype — under development.
