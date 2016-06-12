#Project Documentation

#### Servers

<dl>
  <dt>Testing Server: </dt>
  <dt>http://198.101.242.235/</dt>
</dl>  

<dl>
  <dt>Production Server: </dt>
  <dt>http://198.101.242.203/</dt>
</dl>

#### Deployment Plan

###### Deploy an Ubuntu Server with DigitalOcean
1. Create New User
2. Select Server Size
3. Select Image (Ubuntu 12.04.5)


###### Live Server and Test Server Setup
1. SSH Into the Server 
2. Create Non-Root User
3. Update Package System
4. Update System level Packages
5. Install Packages
⋅⋅* Apache
..* Git 


###### GitHooks Deployment
1. Create Space for Repo on Live Server 
2. Configure Server Post Hook 
3. Configure Local Dev Environment 
⋅⋅1. Create Live and Testing remotes for both servers
⋅⋅2. Create branches to help identify project changes
⋅⋅3. Add and Commit changes to branch
⋅⋅4. Push changes once confirmed everything is working properly


⋅⋅⋅ Primarily work in testing server for creating branches for constant changes and debugging
⋅⋅⋅ once site is showing the way you like then create a branch for new testing changes add and commit
⋅⋅⋅ that branch and merge it into master (LiveServer) push once you are sure your corrections were correct.