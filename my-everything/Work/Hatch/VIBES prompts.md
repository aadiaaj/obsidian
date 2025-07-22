**Prompts for component creation in Hatch application - before task delegation**

VSCode Copilot: Agent, Claude 3.7 Sonnet

**ME:**

“Use the /docs/db/PRD.md file to populate the /components/docs/features-and-components.md file with a list  of all of the features and components necessary for the frontend of the custom GPT application  

Components: Reusable code used to build out one individual component
Features: Reusable code that consists of a blend of components

Create a list of all the components. Create a list of all of the features, with a list of what components are needed for each feature.

We will be utilizing shadcn and originui. Do not create the actual components yet. Ask me questions before creating the plan.”

  

**COPILOT:**

1. Are there any specific design patterns or UI elements you'd like to prioritize from shadcn or originui?
2. Do you have any preferences for how the component structure should be organized (atomic design, feature-first, etc.)?
3. Are there any specific components from the PRD that you'd like me to focus on more than others?
4. Do you have any existing design mock-ups or wireframes I should be aware of?

  

**ME:**

1. Prioritize shadcn and use origin UI if shadcn does not have what we need. Also, use the ui/src/styles.css file we have for all tailwind customization
2. Atomic design will go in a /components/atoms/ folder and features will go into a /components/features folder. As the individual atoms and features are created, make sure they also have their own folder with the same naming convention as their file.
3. Focus on the frontend development.
4. Yes. 

  

**COPILOT:**

Added to features-and-components.md file

  

**ME:**

Also add in the following:

- Use shimmer for loading states

- Create a footer

  

**ME:**

Now use the features-and-components.md file to create individual documentation (.md) for each component and feature. Place each document in the folder of its own atom or feature.

  

Ask me questions before executing.

  

**COPILOT:**  
I'll help you create individual documentation files for each component and feature from the features-and-components.md file. Before I execute, I need to understand a few things:

  

1. Should I create the directory structure for components and features if they don't exist already?

2. Do you want me to follow a specific structure or template for each documentation file?

3. Should I organize the atoms in a specific way (like UI Elements, Data Display, etc.) as shown in the main document?

4. Would you like each documentation file to include additional details beyond what's in the main document, such as implementation notes or examples?

  

**ME:** 

1. Yes.
2. Similar to how you created the features-and-components.md file
3. No
4. No

  

**ME:**

**The toggle variant in the checkbox may be too simian**


---

GPT Enterprise (4o-mini?)

![[Screenshot 2025-05-22 at 4.37.13 PM.png]]
Copilot / Claude 3.7 Sonnet / Agent
@workspace

Use overview.md to create the SolutionOverview.tsx feature file in the components/features/solution-detail folder


Ask me questions before developing.

If the component already exists in the repo, use it. If not, import from shadcn