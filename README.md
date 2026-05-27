## Core concepts - Roles in LLM:

a. System Role (Most important):
     - It defines the behaviour, scope, constraints of the LLM
     - It acts like a policy layer for the LLM
     E.g. "You are a strict banking assistant. Only answer questions related to Banking and finance. anything else, you reply as - I dont know"

b. User Role:
     - It is an actual input/query from the user
     - Dynamic in nature
     E.g. " What is my savings account balance?"
    
c. Assistant Role:
     - It models the response generated
     - Maintain conversation continuity
     E.g. " A saving account is ......"