# 🏛️ LLaMA 2 Finetuned Chatbot for Indian Monuments

This project presents a conversational chatbot fine-tuned on the **LLaMA 2 13B GPTQ model** to provide information about various famous Indian monuments.

---

## 🚀 What This Project Does

- Utilizes a **quantized version of LLaMA 2 (13B Chat GPTQ)** hosted on Hugging Face.
- Allows users to interact with the model via a simple text-based interface in **Google Colab**.
- The chatbot responds to questions about 24 well-known Indian monuments such as:
  - Taj Mahal
  - Qutub Minar
  - Ajanta & Ellora Caves
  - Hawa Mahal
  - Golden Temple
  - Charminar
  - Sun Temple Konark
  - Mysore Palace
  - And many more
- A **system prompt** is used to instruct the model to behave like a heritage tour guide focused only on these monuments.
- **Text-generation pipeline** from Hugging Face is used to generate relevant and informative responses.
- A **token-check utility** ensures the prompt stays within the model’s input limit.
- The chatbot keeps a record of user-assistant conversation to maintain context between turns.

---

## 📚 Learning Outcome

- Understood how to load and interact with large language models like LLaMA 2 GPTQ in Colab.
- Learned to fine-tune the conversational flow using system prompts.
- Explored the use of quantized models to run large-scale LLMs efficiently on limited resources.
- Gained experience with Hugging Face's pipeline API for deploying interactive NLP systems.

---

## 💡 Future Work

- Improve the user interface using Gradio or Streamlit.
- Add more context-aware memory handling between turns.
- Integrate a monument image classifier to complement the chatbot responses.

---

## ✅ Prerequisites

- Google Colab (recommended for GPU support)
- Hugging Face `transformers`, `auto-gptq`, and `optimum` libraries

---

## 📌 Note

All code is available and runnable in the Colab notebook in this repository. No API keys are needed since the model is accessed directly via Hugging Face.

---

## 👨‍💻 Author

**Jyothula Bhaskar**  
B.Tech in Computer Science & Engineering (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/bhaskar-jyothula-974bbb271/) | [Hugging Face](https://huggingface.co/Bhaskar2611) | [GitHub](https://github.com/Bhaskar2603) | [Kaggle](https://www.kaggle.com/bhaskarjyothula)

---

## 🙏 Acknowledgements

- Special thanks to **Medium Daily Digest** for its invaluable insights and inspiration.
- Gratitude to the Hugging Face community and all open-source contributors for providing the tools and resources that made this project possible.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.


