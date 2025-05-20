#  GitMaster: Advanced Git & Open Source Workflows

![GitMaster Banner](https://images.unsplash.com/photo-1556075798-4825dfaaf498?auto=format&fit=crop&q=80&w=1200&h=300)

A comprehensive interactive guide to mastering advanced Git workflows and contributing to open source projects.

## 🚀 Features

- **Fork & Clone Workflow**: Learn how to fork repositories, add upstream remotes, and keep your fork in sync
- **Cherry-Pick Commits**: Master the art of cherry-picking specific commits across branches
- **Semantic Versioning**: Create annotated tags following semantic versioning and publish GitHub releases
- **Interactive Rebase**: Perform interactive rebases to maintain a clean commit history

## 📋 Project Structure

```
src/
├── assets/
│   └── favicon.svg
├── components/
│   ├── CommandExample.tsx   # Renders command examples with output
│   ├── Footer.tsx           # Site footer component
│   ├── Header.tsx           # Navigation header with responsive menu
│   └── WorkflowStep.tsx     # Component for workflow step display
├── pages/
│   ├── CherryPick.tsx       # Cherry-pick tutorial page
│   ├── ForkWorkflow.tsx     # Fork workflow tutorial page
│   ├── Home.tsx             # Landing page
│   ├── InteractiveRebase.tsx # Interactive rebase tutorial page
│   └── Tagging.tsx          # Semantic versioning & tagging page
├── App.tsx                  # Main app component with routing
├── index.css                # Global styles and Tailwind customizations
└── main.tsx                 # Entry point
```

## 🛠️ Technology Stack

- React with TypeScript
- React Router for navigation
- Tailwind CSS for styling
- Lucide React for icons

## 🔧 Local Development

### Prerequisites

- Node.js 14.0 or later
- npm 7.0 or later

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gitmaster.git
cd gitmaster
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser to `http://localhost:5173`

## 📖 Learning Objectives

This project covers essential Git workflows:

1. **Fork & Clone Workflow**
   - Forking repositories on GitHub
   - Cloning your fork locally
   - Adding upstream remotes
   - Fetching and merging upstream changes
   - Pushing changes to your fork

2. **Cherry-Pick Workflow**
   - Identifying commits to cherry-pick
   - Cherry-picking commits from one branch to another
   - Resolving conflicts during cherry-picking
   - Creating pull requests from cherry-picked commits

3. **Semantic Versioning & Tagging**
   - Understanding semantic versioning principles
   - Creating annotated Git tags
   - Pushing tags to remote repositories
   - Creating GitHub releases with release notes

4. **Interactive Rebase**
   - Squashing multiple commits into a single commit
   - Editing commit messages
   - Rearranging commits
   - Force pushing with safety precautions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
