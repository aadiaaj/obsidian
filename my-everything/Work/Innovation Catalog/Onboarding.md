**Innovation Catalog**
Demos, case studies, and ongoing R&D projects
- Title, media, description, tag, external links, etc.

“Try it out” —> external link

“Contact us” —> 

Searching capability

**V2**:
1. **Admin page**
2. SSO

  

**Backend - Saugaat**
Search feature pipeline
1. Get folders from project directory in azure blob storage

RAG pipeline for what it is, why it matters, key features, and tags descriptions for each project
/projects endpoint

Action items:
- Optimize runtime for searching capability:
- Currently using 4.0
- Test out 3.5 and/or gemini runtime and quality of input

**Frontend - Marek**
When changes are made:

1. Goes through dev site first
2. Needs approval to go through

[innovationcatalog.pwcinternal.com/api/docs](http://innovationcatalog.pwcinternal.com/api/docs) | password protected
**APIs**:
Get
- get information without changing anything
/projects
- Get what page and how many is the limit
- Used for optimization so all pages don’t load at once
- If null, it fetches all the projects
- Each project has it’s own id
- Slug: end section of a url; if someone has the same project title, the slug will update
/projects/{identifier} = Want information about a particular project
- Input is id or slug
- 404 error if project not found 
/projects/{project_id{/documents
- Returns media and documents for each project
Search
/suggest = auto suggest
- Only looking at title for autosuggest; later it will look at 
/search
—> query, response, and projects
—> required input: “question”: “what is Iot”
—> search should work for titles and all other project information
—> optimize in the future 

Database access is much faster than an AI service
Database
Tables:
- Projects
- Documents 
- Document chunks
- Search queries

Technical documentation

  

  

ADO

- Api: backend
- Serveless: pending
- ui: UIX

  

Branches: use development branch

  

Backend/routers/

  

  

**FRONTEND**

  

Code base: NextJS, scss,

- NextJS scss pages need to have .module.scss at the end the name

  

Not-found: error page

  

App ? Main ? layout.tsx

  

App > main > page

- Landing page

  

App > main ? Search > page

- Search page

  

App > main > catalog:

- Config additional data
- Catalog page, is the main page when clicking “R&D”
- > id:

- Individual page after clicking into a project

  

Assets:

- Icons

  

Components = general component library w/ PwC branding that we can use; full of individual components 

- Individual components
- Library components
- Not related to business features; general templates

  

Constants:

- urls
- appConfig: 
- Iconsconfig

- Remain consistency between icons

  

Features = components we’re actually using; usually a combination of the general components

- Components on he pages that are related to the business branding
- Components that we’re actually using

  

Questions;

- Where did these components come from?

  

How to get running locally: in [READ.me](http://READ.me)

- npm install & npm run dev

  

Used nextJS

  

  

**Action items**

- Familiarize with what endpoints are connected to what
- Look at technical documentation
- Download code locally
- Familiarize with frontend code and get running locally
- Making search endpoint fasteer

  

  

**Questions**

  

- Why did we choose to make components from scratch instead of using a library like Appkit or ShadCn?
- What is this storybook page?
- On the R&D page

- why does the left side with the filters have a mobile and desktop div? And other components do not?

- When clicking into a single project:

- I don’t think “Key Features” has a default message if there’s no data.
- The mailto button only opens up an email to the first person
- Are there supposed to be “support links” under the media section