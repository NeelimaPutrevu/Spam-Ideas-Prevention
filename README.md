# Spam-Ideas-Prevention
To prevent Spam Ideas being created/ posted which are built on top of Modern Community template.
Following feature are implemented:
1. Deactivate Spam Ideas and Lockout Site User/Contact: Prevent Spam Ideas by locking out the site user and deactivate their ideas if user posts excessive number of Ideas based on the below conditions:
    a. If user posts more than 3 ideas in the past 10 minutes
    b. If user posts more than 10 ideas in the past week
    c. If user posts more than 50 ideas in the past month
2. Mark Ideas as 'Spam' from Model-driven App
3. Delete Spam Ideas after 6 months
4. Whitelist geniune site User by unblocking them
5. The current repository contains 2 Managed solutions 'ModernCommunity_SpamPrevention’ and 'ModernCommunity_WhitelistContact'.
6. The Target environment should have the entity Idea (msdyn_cmty_idea) added as a pre-requisite step for the solutions to get deployed successfully.
