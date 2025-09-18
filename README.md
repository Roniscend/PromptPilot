# PromptPilot

## Project Description
An AI debugging assistant prompt engineered to guide language models in providing educational Python debugging support without revealing direct solutions.

## Setup Instructions

### Requirements
- Access to any AI language model
- No additional software dependencies required

### Installation and Usage

1. Clone the repository:
git clone https://github.com/Roniscend/PromptPilot.git

2. Copy the prompt:
- Open `prompt.txt`
- Copy the entire content

3. Deploy to AI assistant:
- Navigate to your preferred AI language model interface
- Paste the complete prompt content
- Press Enter to activate the debugging assistant

4. Begin debugging sessions:
- Students can submit Python code containing errors
- The AI will provide structured educational guidance

### Example Usage
Student Input: Python code with syntax or logic errors
AI Output: Guided questions leading to self-discovery of solution

## Repository Structure
PromptPilot/
├── prompt.txt
├── README.md 
## Design Choices and Reasoning

### Why you worded it the way you did
The prompt uses structured, systematic language with explicit constraint definitions to ensure consistent educational outcomes. I implemented a six-step response protocol and clear "FORBIDDEN/REQUIRED" actions to create predictable, high-quality interactions. The pedagogical terminology establishes the AI's educational mission while the multi-layered framework ensures comprehensive debugging guidance across all Python concepts.

### How you ensured it avoids giving the solution
Solution avoidance is achieved through multiple reinforcement mechanisms: explicit prohibitions against providing corrected code, a progressive four-level questioning system that guides discovery without revealing answers, and quality assurance checkpoints. The prompt includes redirect protocols for direct solution requests and focuses investigation suggestions on debugging techniques rather than problem fixes, preserving learning value through self-discovery.

### How it encourages helpful, student-friendly feedback
Student-friendly feedback is fostered through mandatory acknowledgment of effort, positive language patterns, and progress-based encouragement. The adaptive competency system matches communication to skill level while the structured approach guarantees practical next steps, conceptual connections, and momentum-building support in every interaction, creating a motivating learning environment.
### What tone and style should the AI use when responding?
The AI employs an encouraging, educational tone with professional warmth that adapts to student skill levels. The communication style emphasizes patient guidance through strategic questioning rather than direct instruction, using clear, accessible language that builds debugging intuition alongside immediate problem resolution while maintaining student confidence throughout the learning process.

### How should the AI balance between identifying bugs and guiding the student?
The AI achieves optimal balance by allocating 30% to strategic problem identification (pointing to code areas without revealing fixes), 50% to guided discovery through progressive questioning, and 20% to investigation methodology suggestions. This structure preserves student agency while providing sufficient scaffolding to prevent frustration and maintain learning momentum.

### How would you adapt this prompt for beginner vs. advanced learners?
For beginners: simplified vocabulary, explicit concept explanations, single-issue focus, and increased encouragement with concrete steps. For advanced learners: technical terminology, professional tools, design implications, and architectural considerations. Adaptation relies on competency inference from code complexity, naming conventions, and demonstrated problem-solving approaches, ensuring appropriate challenge levels across all skill ranges.

## Submission Details
- **Project**: FOSSEE Python Internship
- **Task**: Screening Task 2 - AI Debugging Assistant Prompt
- **Submitted**: September 2025
- **Contact**: pythonsupport@fossee.in
