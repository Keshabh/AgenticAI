- **Pydantic helps check if your data is correct in Python.**
- You make a *class* for your data and say what type each item should be.
- If you give wrong types, Pydantic shows an error.
- You can make some items optional or set default values.
- It checks lists (like numbers or words) and even data inside data.
- You can limit things—like minimum/maximum for numbers or text length.
- Pydantic auto-builds schemas for API docs.
- Use Pydantic models at every step in LangGraph for safe workflows.
- It blocks bad data from moving through your AI system.
- Using Pydantic means fewer bugs and smoother automation!
- FAST API also uses Pydantic a lot.
- In Agentic AI, we have multiple AI agents i.e software programs each working on a specific task to achieve a single goal, where they need to communicate with each other a lot, inorder to make sure, their communication does not have any gaps due to invalid data types, we have pyDantic.
- Ex: If one agent generated a string, and another agent which is supposed to use the output of agent 1 expects an integer, then thats a mismatch, and they wont be able to communicate, and that is where we need to use pyDantic, either agent 1 generates int so agent 2 can use it,
or agent 1 generates string so agent 2 can use it.

***

This version keeps it simple and covers all important points.

[1](https://www.youtube.com/watch?v=vVGXPRjtAJE&list=PLZoTAELRMXVPFd7JdvB-rnTb_5V26NYNO&index=3&t=1172s)


- **Create Virtual Environment**
- python -m venv venv

- **Activate Virtual Environment**
- venv\Scripts\activate

- **Install Must Libs Before Accesing Jupyter Notebook**
- pip install ipykernel ipython jupyter

- **Register Jupyter Kernel**
- python -m ipykernel install --user --name=venv

- **Select Kernel**
- Go to top right, and select the kernel(select the environment just created)
- Install Libs Inside this enviroment remains in this virtual environment only

- **To confirm if the correct kernel has been connected or not**
- import sys
- print(sys.executable)
