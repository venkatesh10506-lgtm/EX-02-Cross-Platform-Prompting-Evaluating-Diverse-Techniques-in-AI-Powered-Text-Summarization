# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform thaat delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

The experiment begins by defining the use case, which is to evaluate different AI platforms on a common task such as summarizing or answering a technical question. A uniform prompt is prepared to ensure fairness across platforms like ChatGPT, Claude, Bard, Cohere Command, and Meta. The same prompt is then given to each AI tool under identical conditions, and the responses are collected. After gathering the outputs, the responses are evaluated based on accuracy, clarity, depth, relevance, and response time. The performance of each platform is then compared using these evaluation criteria, and the results are recorded in a comparison table. Finally, the overall findings are analyzed to determine which platform provides the most effective response for the given use case, and the conclusions are documented in the report.

## Result
## Outputs from Different AI Platforms:
## ChatGPT:
Machine Learning, according to ChatGPT, is best understood as a branch of Artificial Intelligence that allows systems to detect patterns in large datasets and make predictions without relying on explicitly written rules. Instead of following fixed, human-coded instructions, a machine learning model improves progressively as it encounters more examples over time. For instance, ChatGPT highlights the spam detection system in email services. By training on thousands of labeled examples of “spam” and “not spam,” the model automatically learns how to distinguish between the two and applies this knowledge to filter new, unseen emails. This explanation is highly structured, technically accurate, and framed in an academic tone. It is particularly useful for undergraduate students who want a clear yet slightly formal introduction to the concept.

<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/e61be195-abab-40eb-ad35-49a680abe409" />


## Claude:
Claude explains Machine Learning in a more conversational and analogy-driven style. It frames the concept as teaching computers to learn from examples, much like training a student by practice rather than by memorizing rigid instructions. This perspective makes the explanation approachable and intuitive for beginners who might otherwise find technical definitions overwhelming. Claude provides the relatable example of Netflix recommendations. By observing a user’s viewing history and analyzing the patterns of similar users, Netflix predicts and suggests movies or shows the person may like. The analogy of “training a student” makes Claude’s explanation student-friendly and engaging, although it trades some technical depth for simplicity.

<img width="485" height="104" alt="image" src="https://github.com/user-attachments/assets/74410643-b608-4fff-ac44-578194a66878" />

## Bard/Gemini:
Bard approaches the concept of Machine Learning from a highly practical lens, emphasizing its role in real-world applications. It explains ML as a process where computers enhance their performance by analyzing large volumes of data and identifying patterns, thereby creating their own set of rules instead of being explicitly programmed. The example provided is Google Maps traffic prediction, which is a service widely used and understood by students. By analyzing past traffic data and current conditions, Maps is able to forecast congestion and suggest the fastest available route. Bard’s explanation is straightforward and realistic, giving learners a clear view of how ML affects their daily lives. It is particularly effective for students who prefer practical use cases over theoretical detail.

<img width="312" height="112" alt="image" src="https://github.com/user-attachments/assets/264e03a7-b9a3-4ba3-9315-9cea3f8a5dfb" />

## Cohere Command:
Cohere defines Machine Learning in a very simple and concise manner, focusing on its adaptability and predictive capabilities. It highlights that, unlike traditional programming where rules are predefined, ML systems learn to recognize trends and update their predictions when new information arrives. Cohere provides the example of product recommendations on e-commerce platforms. When a user buys a phone, the system is able to suggest complementary items such as headphones, chargers, or covers by analyzing the purchasing behavior of other customers. This explanation is minimal and easy to understand, making it useful for absolute beginners who are just getting introduced to the field. However, its brevity also means it lacks the depth and layered detail seen in ChatGPT or Bard’s responses.

<img width="394" height="128" alt="image" src="https://github.com/user-attachments/assets/4dfddd00-45a3-4037-bb16-a8de778d8abb" />

## Meta (LLaMA):
Meta’s LLaMA describes Machine Learning as a method for systems to automatically improve accuracy and performance over time through exposure to data, without being explicitly coded with rules. The explanation is straightforward and emphasizes the progressive learning aspect of ML. The example provided is voice assistants like Siri and Alexa, which gradually adapt to a user’s speech, accent, and phrasing patterns, becoming more accurate as they are used. This example is relatable and clearly demonstrates the real-world utility of ML. However, the explanation remains somewhat generic and less polished compared to ChatGPT’s academic depth or Claude’s analogy-driven style. It is best suited for readers who want a direct and correct answer without much extra framing.

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/47677248-7061-40a2-abf6-f6987a700c19" />

## Comparison Table:
| **AI Platform**             | **Role/Personality Style** | **Strength**                                | **Weakness**                         | **Example Used**               | **Best Suited For**                    |
| --------------------------- | -------------------------- | ------------------------------------------- | ------------------------------------ | ------------------------------ | -------------------------------------- |
| **ChatGPT (OpenAI)**        | 🧑‍🏫 Professor            | Clear, structured, academically strong      | Slightly formal, less conversational | Email spam detection           | Classroom explanations, detailed notes |
| **Claude (Anthropic)**      | 👩‍🎓 Friendly Tutor       | Relatable, uses analogies, student-friendly | Less technical depth                 | Netflix recommendations        | Beginners, casual learners             |
| **Bard/Gemini (Google)**    | 🗺️ Practical Guide        | Real-world focus, connects with daily apps  | Less detailed in theory              | Google Maps traffic prediction | Learners who like applied knowledge    |
| **Cohere Command (Cohere)** | 📝 Minimalist Explainer    | Simple, direct, quick to grasp              | Limited depth, less engaging         | E-commerce product suggestions | Quick introductions, short sessions    |
| **Meta (LLaMA/AI)**         | 🎤 Generalist Speaker      | Correct, engaging, uses familiar tools      | Generic, lacks uniqueness            | Voice assistants (Siri, Alexa) | General overviews, casual audiences    |

## Comparison chart Visualise:

<img width="1980" height="1180" alt="image" src="https://github.com/user-attachments/assets/07858884-e330-4524-ae15-f3d3866a330c" />


## Result:

The experiment successfully compared ChatGPT, Claude, Bard, Cohere Command, and Meta on the technical question answering task.

ChatGPT and Claude gave the most accurate and clear explanations, suitable for undergraduates.

Bard provided highly practical real-world examples.

Cohere and Meta were simpler but slightly less detailed.
Overall, ChatGPT and Claude performed best for clarity and depth, while Bard excelled in real-world application examples.

