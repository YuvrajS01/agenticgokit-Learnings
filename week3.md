I learned about MultiAgent Workflows
So Basically we give each agent it's role
we have some orchestrator agents, research agents, tool specific agents.
After defining the role we then set the workflow order
the order can be sequential, looping, or anything else depending on the work.
once we have our agent order setup we go to the next set of using and testing the agent

We give some input then which is passed together with data from some vector DB.

vector DB is especially important because all the data for AI work is stored in the forms of vector at a higher dimesional space
and doing fuzzy searches is far easier in vector db instead of relational DB

Now next is memory: 
memory can be of two types one which is stored in vector DB for long term storage
the next is context the current session messages which are retained by the LLM to produce results using previously sent messages it is low compared to vector db

next up is MCP:
MCP is a standard protocol of connecting tools with LLM to increase their functionality.
with MCPs LLMs and Agents can do various tasks like using web browsers or using tools like figma
