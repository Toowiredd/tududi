# Agent Guidelines

This project uses Ruby, Sinatra, and React. The user has ADHD 2e, aphantasia, and anendophasia.
Agents should:

- Offer step-by-step instructions with brief bullet lists.
- Provide explanations that do not rely on images or internal speech cues.
- Keep commit messages short and clear.

## Setup

Run these commands to prepare the environment:

```bash
bundle install
yarn install
rake db:setup
```

## Running the App

Start the server with:

```bash
puma -C app/config/puma.rb
```

Use `.rubocop.yml` for Ruby style rules. Check `README.md` for required environment variables.
