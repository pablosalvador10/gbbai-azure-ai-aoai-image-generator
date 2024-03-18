# <img src="./utils/images/azure_logo.png" alt="Azure Logo" style="width:30px;height:30px;"/>  Image Generation and Multimodal Evaluation with Azure OpenAI

Welcome to this comprehensive guide designed to help developers build robust architectures and applications for multimodal image generation and evaluation using Azure OpenAI. The focus is on using the DALL-E model v3 and the GPT-Vision model to generate images, refine them, and evaluate their quality and relevance.

## Enhancing Image Generation with Prompt Engineering in DALL-E 3

### 🎯 Harnessing the Power of Detailed Descriptions

Consider the task of creating an image of a soccer stadium. Instead of a simple "soccer stadium", we can enhance our description: "a sprawling soccer stadium under a twilight sky, filled with thousands of cheering fans, the field immaculately maintained, and the stadium lights casting a warm glow on the scene."

This level of detail in our prompt guides DALL·E 3 to generate an image that closely matches our envisioned scene. The rule of thumb is: the more specific your description, the better the outcome will align with your vision.

### 🎨 Guiding the Outcome with Details

By specifying attributes such as the time of day, the state of the field, and unique details like the stadium lights, we steer the AI to concentrate on these elements. This precision becomes crucial when creating a theme or narrative across multiple images, ensuring the subject remains recognizable and consistent.

For instance, if we're creating a series of images for a story about a "sprawling soccer stadium under a twilight sky", maintaining these specific details in our prompts will ensure the stadium is easily identifiable throughout the story.

### 🚀 Balancing Consistency and Creativity with Specificity

Detailed prompts not only ensure consistency but also encourage creative exploration within a set framework. For example, changing the stadium's state from filled with fans to being empty and quiet, while keeping the detailed description, ensures that the stadium’s key characteristics remain intact.

This strategy of using detailed prompts serves two purposes: it maintains the subject's continuity across variations and enriches the narrative or theme, making each image a unique yet coherent part of the story.

## 🎯 Crafting the Prompt


> "Imagine a majestic soccer stadium as the setting for an epic final match. The scene unfolds on a crisp, early spring evening, just as the sun dips below the horizon, casting a soft, golden light across the scene. The stadium, an architectural marvel, features sweeping curves and towering stands, filled to the brim with fans clad in a vibrant tapestry of team colors, their faces alight with anticipation. The meticulously maintained green pitch stands in stark contrast to the darkening sky, underlined by the bright, artificial lights that begin to take over, creating dramatic shadows and highlighting the players' every move. Around the stadium, the city skyline begins to twinkle, mirroring the excitement inside."

This detailed prompt guides DALL·E 3 to generate an image that closely matches our envisioned scene. The more specific your description, the better the outcome will align with your vision.

Here's the resulting image:

![Soccer Stadium](./utils/images/soccer_stadium.jpeg)

## 🛠️ How-to 

This guide adopts a problem-solution approach, pairing each challenge with a detailed explanation and a complementary set of Jupyter notebook.

* [**Image Generation with DALL-E 3**](#image-generation-with-dall-e-3): Learn how to generate images using the DALL-E model v3 api.
* [**Feedback Loop using GPT-4+Vision**](#feedback-loop-using-gpt4-vision): Discover how to refine the image generation process by incorporating feedback obtained from the GPT-Vision model (multimodality).

> Please refer to the 'Prerequisites' section before proceeding.

## 🔧 Prerequisites

Please make sure you have met all the prerequisites for this project. A detailed guide on how to set up your environment and get ready to run all the notebooks and code in this repository can be found in the [SETTINGS.md](SETTINGS.md) file. Please follow the instructions there to ensure a smooth exprience.

## 💼 Contributing:

Eager to make significant contributions? Our **[CONTRIBUTING](./CONTRIBUTING.md)** guide is your essential resource! It lays out a clear path.

- To stay updated with the latest developments and document significant changes to this project, please refer to [CHANGELOG.md](CHANGELOG.md).


