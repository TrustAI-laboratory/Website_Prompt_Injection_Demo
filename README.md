# Website_Prompt_Injection_Demo
Website Prompt Injection is a real world attack that allows for the injection of prompts into an AI system via a website's document. This technique exploits the interaction between users, websites, and AI systems to execute specific prompts that influence AI behavior.

# How it Works
The process involves hiding prompts within the frontend code of a website, typically in a manner that remains invisible to human users. When a user requests the AI to access or interpret the content of the website, the AI system inadvertently reads the concealed prompts embedded within the website's frontend. If successful, the AI executes the injected prompt, leading to desired outcomes as dictated by the injected prompt.
![image](https://github.com/user-attachments/assets/ad2eb258-c4b5-40b1-9206-e435cf957126)

The overall attack process is as follows:

* Step1：Embed the desired prompt within the frontend code of the website, ensuring it remains hidden from human users, but notAI systems. You can use one of our html examples in this repository

* Step2：Ensure that the AI system interacts with the website's frontend code to interpret the content. This can be done by asking GPT4 or other systems to read the website and provide a summary (such as “please help me to describe the page link：“, etc.). Even in the foreseeable future, artificial intelligence systems will be integrated by default in Apple IOS and Chrome, for example, which will automatically read web page content in the background and generate summaries when users browse the web.

* Step3：Upon reading the hidden prompt, the AI system should execute the specified action, influencing its behavior based on the injected prompt.

# Conclusion
This article about the Website Prompt Injection is to demonstrate the potential vulnerabilities of AI systems when interacting with web-based interfaces.

By showcasing this concept, we aim to raise awareness about the importance of robust security measures in AI systems, particularly in scenarios involving user-generated content and external interactions.
