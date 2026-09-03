1
text = f"""
OVERVIEW
- Inspired office chair.
- Aviable with plastic back and front.
- Base finish options: stainless, steel, mate black, gloss withe, or chrome.

CRONSTRUTION
- 5-wheel plastic coated aliminium base.

DIMENSIONS
- WIDTH 53 CM
DEPTH 51 CM
"""
prompt = f"""
Write a product description for this chair
Technical specifications:
```{text}```
"""
response = get_completion(text)
print(response)

2
text= f"""
I never expected to find a dragon in my backyard...
"""

prompt = f"""
Continue the history with the text that I wrote
```{text}```
"""

response = get_completion(text)
print(response)

3
text = f"""
Ingredients
600 g of cream cheese, like Philadelphia
200 g of sugar
4 medium eggs
200 ml of heavy cream (35% fat)
1 tsp vanilla extract or lemon zest
1 tbsp wheat flour or cornstarch
Optional: red berry jam for serving

Preparation
Preheat the oven to 190 °C (375 °F) with top and bottom heat. Line a 22 cm springform pan with parchment paper.

Beat the cream cheese with the sugar until smooth. Add the eggs one at a time.

Stir in the cream, vanilla/zest, and sifted flour. Mix until you get a smooth cream.

Pour into the prepared pan and bake for 50–55 minutes, until the top is golden and the center is slightly wobbly.

Let it cool in the turned-off oven with the door slightly open. Refrigerate for at least 4 hours before serving.

Serve with red berry jam or fresh fruit.
"""

prompt = f"""
According to these ingredients and how it's prepared, what is the recipe for?
```{text}```
"""
response = get_completion(text)
print(response)


4
text = f"""
Ingredients
600 g of cream cheese, like Philadelphia
200 g of sugar
4 medium eggs
200 ml of heavy cream (35% fat)
1 tsp vanilla extract or lemon zest
1 tbsp wheat flour or cornstarch
Optional: red berry jam for serving

Preparation
Preheat the oven to 190 °C (375 °F) with top and bottom heat. Line a 22 cm springform pan with parchment paper.

Beat the cream cheese with the sugar until smooth. Add the eggs one at a time.

Stir in the cream, vanilla/zest, and sifted flour. Mix until you get a smooth cream.

Pour into the prepared pan and bake for 50–55 minutes, until the top is golden and the center is slightly wobbly.

Let it cool in the turned-off oven with the door slightly open. Refrigerate for at least 4 hours before serving.

Serve with red berry jam or fresh fruit.
"""

prompt = f"""
Tell me the nutritional information of this cheesecake per serving
```{text}```
"""
response = get_completion(prompt)
print(response)


5
text = f"""
Artificial intelligence (AI) is a technology that allows machines to perform tasks that normally require human intelligence, such as analyzing data, recognizing patterns, generating content, or making decisions based on available information.

In the business world, AI is used to automate repetitive processes, improve customer service through chatbots, optimize inventory management, predict market trends, and increase employee productivity.

Some of the main benefits include reducing operational costs, improving decision-making through the analysis of large amounts of data, increasing efficiency, and being able to offer more personalized experiences to customers.

However, implementing AI also presents challenges, such as the need to protect data privacy, ensure the ethical use of technology, , adapt to changes in job positions and train employees in new digital skills. In the coming years, AI is expected to play an increasingly important role in organizations, driving innovation, competitiveness, and digital transformation in practically all economic sectors. This text is pure information, ready for you to later turn it into a prompt.
"""

prompt= f"""
Summarize the following text in clear and concise language, highlighting the most important ideas:
```{text}```
"""
response = get_completion(prompt)
print(response)

6
text = f"""
Reading is one of the most beneficial activities for personal and professional development. Through books, people can acquire new knowledge, improve their comprehension skills, and expand their vocabulary. In addition, reading frequently stimulates creativity, strengthens memory, and contributes to the development of critical thinking.

In the digital age, access to information is easier than ever thanks to e-books, virtual libraries, and online educational platforms. However, many people spend less and less time reading due to the constant use of social media and the consumption of audiovisual content.

Various studies have shown that those who maintain the habit of reading tend to develop better communication skills, greater concentration, and more effective learning. For this reason, encouraging reading from an early age is a key strategy to improve education and promote the intellectual growth of society.
"""

prompt= f"""
Explain this text forthe kids of 10 years old
```{text}```
"""
response = get_completion(prompt)
print(response)

7

text= f"""
The Apollo 11 mission was one of the most important space expeditions in history. It was launched by NASA on July 16, 1969, from the Kennedy Space Center in Florida. The crew consisted of Neil Armstrong, Buzz Aldrin, and Michael Collins.
After four days of travel, the spacecraft reached lunar orbit. On July 20, 1969, the Eagle lunar module landed on the surface of the Moon with Armstrong and Aldrin on board, while Collins remained in orbit. A few hours later, Neil Armstrong became the first human being to walk on the Moon and famously said, "That's one small step for man, one giant leap for mankind."
During their stay on the lunar surface, the astronauts collected rock samples, conducted scientific experiments, and installed several measuring instruments. After completing their mission, they returned to Earth and landed in the Pacific Ocean on July 24, 1969.
The success of Apollo 11 marked a milestone in space exploration and demonstrated the technological capabilities of the era. It also inspired future space programs and increased global interest in scientific research and the exploration of space.
"""

prompt= f"""
Generate 10 multimpe-choice questions
```{text}```
"""
response = get_completion(prompt)
print(response)

8
text= f"""
The XPhone Pro was released earlier this year and quickly attracted attention due to its advanced camera system and long battery life. Many users praised the device's performance, noting that applications launch quickly and multitasking is smooth.
However, some customers reported concerns regarding the price, arguing that competing smartphones offer similar features at a lower cost. Others mentioned that while the hardware is impressive, the software interface can be difficult for new users to navigate.
Overall, customer reviews have been largely positive, with most buyers expressing satisfaction with the phone's reliability and premium design.
"""

prompt= f"""
Do the pros and cons of XPhone Pro
"""
response = get_completion(prompt)
print(response)

9 
text= f"""
On March 15, 2024, a multinational technology company detected unusual activity within its internal network. Security analysts discovered that unauthorized users had gained access to several employee accounts through a phishing campaign. The attackers attempted to exfiltrate customer records and confidential business documents.
The company immediately isolated affected systems, reset compromised credentials, and launched an internal investigation. External cybersecurity experts were hired to assess the scope of the breach and recommend improvements to existing security measures.
Although the company stated that no financial information was stolen, it notified regulators and impacted customers as a precaution. The incident highlighted the importance of employee awareness training, strong authentication mechanisms, and continuous monitoring of network activity.
"""

prompt= f"""
Make a timeline events of the incident in the text
```[{text}]```
"""
response = get_completion(prompt)
print(response)


10

text= f"""
Tourism contributes significantly to the economy of many countries. Popular destinations attract millions of visitors each year, creating jobs and supporting local businesses such as hotels, restaurants, and transportation services.
"""

prompt = f"""
Extract the 3 most important keywords from the text.
```[{text}]```
"""
response = get_completion(prompt)
print(response)