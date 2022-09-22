
Tutorials & Workflows
=====================

Testing Changes

While the addon has a lot of options and additional features that you can tweak to achieve different results, there are two basic workflows for creating animated game rigs that you can export to any game engine.

Both workflows require that you already have some sort of a Control Rig for your character. That can be Rigify, Auto-Rig Pro (although Auto-Rig Pro has dedicated tools for game export), or any custom rig.

Workflow 1 - bone hierarchy & bone offset solution for stretching
-----------------------------------------------------------------

This workflow allows you to create any bone hierarchy for your Game rig. You can also achieve limited "squash and stretch" in your character. 

- **What is "squash and stretch"?**
    
    You may be wondering why we are even talking about "squash and stretch". Isn't that a special feature?
    
    The thing is, this is not just about cartoony squash and stretch. Anytime you scale bones in your game rig, it can make your 
    

.. note::
   Prerequisites:
    - a character rigged with a Control Rig
    - all deform bones should be marked with the Deform options and all control bones should have this option disabled.
