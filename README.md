<img width="1390" height="947" alt="Screenshot 2026-06-11 at 17-07-41 OpenBottle AI" src="https://github.com/user-attachments/assets/5cadf382-81db-4868-bf6f-472fc6421701" />

# OpenBottle
OpenBottle is an open-source, locally runnable 3D bottle design platform. Create and customize bottles in real time using interactive controls for dimensions, materials, colors, caps, and contents. Visualize designs in a modern 3D viewer, experiment with different styles, and export bottle concepts for product design and prototyping.

- Create and customize 3D bottle designs.
- Edit bottle dimensions in real-time using sliders.
- Customize materials: glass, wood, transparent plastic, or metal.
- Add liquids or objects inside bottles to visualize different contents (water, juice, sprinkles, etc.).
- Use a modern, minimal UI with interactive 3D viewport.
- Manage projects locally without login or cloud dependencies.

## Features

- **Left Sidebar:** Switch between Design, Materials, Cap Designer, Projects, and Settings.
- **Right Properties Panel:** Edit bottle dimensions, colors, materials, and contents in real-time.
- **3D Viewer:** Rotate, zoom, and pan to inspect bottles from any angle.
- **Parametric Bottle Engine:** Editable geometry based on AI-generated parameters.
- **Material & Content Simulation:** Visualize how liquids and solids appear inside the bottle.
- **Open-Source:** Fully local, runs on Windows/macOS/Linux with Node.js and Next.js.

## Tech Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS, shadcn/ui  
- **3D Engine:** Three.js, React Three Fiber  
- **State Management:** Zustand / React state  
- **AI Integration:** Ollama / Qwen (optional for prompt → parameter conversion)

## Installation

1. Clone the repository in terminal:
   ```bash
   git clone https://github.com/superslangs/openbottle.git

## Open file

2. Run the frontend:
   ```bash
   cd \openbottle\frontend
   
3. Install dependencies:
   ```bash
   npm install

4. Run locally:
   ```bash
   npm run dev

5. Open your browser at http://localhost:3000

   
## Contribution
Contributions welcome! Please open issues or submit pull requests for bug fixes, new features, or UI improvements.
