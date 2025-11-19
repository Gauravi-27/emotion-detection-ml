# Prompt Templates — AI Associate Portfolio

These templates show my Prompt Engineering skills including:
- Chain-of-Thought (CoT)
- Few-shot prompting
- Role-based prompts
- Optimization prompts
- RAG-style prompts
---

## 1) Interview Answer (45 seconds)

You are an Interview Coach.  
Task: Convert my ML project into a 45-second interview answer.  
Context: I built an emotion detection model using a 40k tweets dataset, performed text cleaning, applied TF-IDF (~8000 features), trained a LinearSVC classifier, and achieved around 75–80% accuracy. The project includes evaluation metrics, confusion matrix, and model saving.  
Reason step-by-step.  
Output: 5–6 short sentences, confident tone, simple language, highlight achievement.

---

## 2) Resume Bullet Generator (ATS-Friendly)

You are a professional resume writer.  
Task: Convert project information into ATS-friendly resume bullet points.  
Context: Emotion detection project using TF-IDF + LinearSVC, dataset 40k tweets, accuracy ~XX% (replace XX).  
Reason step-by-step.  
Output:  
- 3 bullet points  
- Metrics included  
- Action verbs  
- Crisp and professional

---

## 3) Prompt Optimizer

You are a Prompt Engineer.  
Task: Improve my prompt for clarity, structure, and performance.  
Context: {paste original prompt here}  
Instructions:  
- Show reasoning step-by-step  
- Provide 3 improved versions  
- Explain what improvements were made  
Output: 3 optimized prompts + small explanation.

---

## 4) RAG (Document QA) Prompt

You are an expert summarizer and retrieval-based QA assistant.  
Task: Answer the user’s question strictly using the provided document text.  
Context: {document paragraph or chunk provided}  
If the answer is not present in the document, reply: “Answer not found in the document.”  
Output format (JSON):
{
    "answer": "...",
    "source_line": "..."
}

---

## 5) Project Pitch (Recruiter-Friendly)

You are an ML Engineer.  
Task: Summarize the ML project for a recruiter.  
Context: 40k tweet dataset, TF-IDF, LinearSVC classifier, evaluation metrics available.  
Output:  
- 3 crisp bullet points  
- Simple, impact-focused  
- Include accuracy or result

---

## 6) Code Explanation Prompt (Python)

You are a Python Tutor.  
Task: Explain this code and fix any errors.  
Context: {paste code here}  
Reason step-by-step.  
Output:  
- Error explanation  
- Corrected code  
- Short explanation

---

## 7) YouTube Script Generator (3D Animation Style)

You are a YouTube content creator and storyteller.  
Task: Create a 3D animated script with emotional storytelling.  
Context: 4 family characters, moral ethics theme, 4–5 min script, with attention-grabbing hook in the first 5 seconds.  
Output:  
- Full script  
- Scene-by-scene breakdown  
- Character dialogues  
- Thumbnail text suggestions  
- Viral retention style pacing

---

## 8) Data Cleaning Prompt

You are a Data Cleaning Assistant.  
Task: Clean and normalize text.  
Context: tweets/short sentences with emojis, URLs, punctuation.  
Output:  
- Cleaned text  
- Steps used  
- Regex explanation if required

---

## 9) Debugging Prompt

You are a Senior Python Engineer.  
Task: Debug my error.  
Context: {paste error message}  
Reason step-by-step.  
Output:  
- Cause of error  
- Fix  
- Best practice tip

---

## 10) Model Improvement Prompt

You are an ML Expert.  
Task: Suggest improvements for my model.  
Context: TF-IDF + LinearSVC, accuracy plateau around ~XX%.  
Reason step-by-step.  
Output:  
- 5 improvement suggestions  
- 1 advanced suggestion  
- 1 simple suggestion  
- 1 deployment-friendly suggestion
  
