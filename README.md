# Problem-Statement-2-Generate-Marketing-Content

Large Language Models are being used extensively in generating marketing content like blogs, emails, social media posts etc.

You are required to build an API in python that takes a topic and a format as input and responds with the text in the desired format. 

Sample : 
Input - 

{
“format” : “linkedin post”,
“topic” : “Generative AI”
}

Output - 
{
“text” : “Excited to share insights on Generative AI! 🚀 With its innovative capabilities, Generative AI is revolutionising various industries, from creative arts to healthcare. Its potential to generate realistic images, text, and even music is reshaping the way we create and interact with technology. Let's explore the endless possibilities and opportunities this cutting-edge technology offers. #GenerativeAI #Innovation #TechRevolution 🤖💡
“
}

Note : You can add other input parameters like emotion, length etc. to make the result better

Deliverable : 
Python code
(Optional) Comprehensive documentation covering API usage, authentication, input processing, response generation, and deployment instructions.
(Optional) A user interface

Hints : 
Use LangChain, OpenAI and BeautifulSoup libraries
In case you’re not familiar with OpenAI, you can refer to this blog - https://medium.com/towards-artificial-intelligence/getting-started-with-openai-the-lingua-franca-of-ai-13864b3c886a
