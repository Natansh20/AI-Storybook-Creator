# AI-Storybook-Creator
Description:
The AI Storybook Creator is an innovative tool leveraging generative AI to transform ideas into engaging illustrated storybooks. Users can enter a topic, and the system generates a short story along with corresponding images. The project integrates advanced text-to-image generation (Stable Diffusion 3 Medium) and a seamless storytelling experience.

### Summarized Pipeline:
Enter Topic or a starting of your choice
* Users can type in a topic or provide a small start of the story.
Generate Story
* Uses GPT-4o mini to create a short story based on the given topic or input.
Generate Images
* The generated story is passed to Stable Diffusion 3 Medium, which produces high-quality corresponding images for each part of the story.
Create Storybook
* Outputs an illustrated storybook combining the generated story and visuals.

### Detailed Pipeline (Including Rationales and Alternatives)
* Overall Stack: Stable Diffusion, OpenAI GPT, Gradio

  * Stable Diffusion 3 Medium: Generates high-quality illustrations from text.
  * GPT-4o mini: Provides contextual and creative story generation.
  * Gradio: Enables a no-code frontend for seamless interaction.

* Text Generation: GPT-4o mini is lightweight and perfect for generating short, structured stories.
* Image Generation: Stable Diffusion is robust for producing detailed and contextually relevant illustrations.
* Frontend: Gradio simplifies the user interface for non-technical users.
