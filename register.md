# Daily Learnings.. Register.


# 12 May 2020
	* Resolved the build Issue:- 
		* CORS issue was resolved by removing the proxy setup from "package.json".
			* By adding prefix url of heroku CORS. (Had Speed issues).
			* Made changes to the API server using flask CORS lib. (Fixed it permanently).
	* HTML basics
		
# 11 May 2020 
	* Created Dynamic Content rendering using a REST API and the React Frontend app.
		* Made use of Class components along with relevant Mapping wrt to the Component and API response.
	* REST API used via Axios.
		* Response for Mapping in JS requires the data to be in list [{"Key":"Value","Key":"Value"},{"Key":"Value","Key":"Value"}]
		* Faced CORS error mitigated it using Proxy in package.json file.
		
	* Works in development mode.
		Shows nothing in production build.
		->>> Issue exists for both isildur13/reactflask and isildur13/react/material-ui-react 
			>> I guess it is a rendering issue..

# 08 May 2020 
	* Setup Bare minimum UI along with Searchbar.
	* Setup Flask API service using prebuilt python util
	* Deployed the Flask API on AWS EC2 and service setup.
	* Communicating using API using functional coponents done.
		* While adding proxy in package.json make sure you restart the dev mode once again to reflect changes.
		* dom restart won't reflect.
	* Pipeline for CD of Flask API done.
	
# 07 May 2020
	* Created UI using Material-UI and React.
		* Grid 
		* State Menu
	* Serious UI creation started.

# 06 May 2020
	* Boxes were vanished.. 
		* Turned out that the machine crash was the issue.
	* Register the vboxes using following command "find /path/to/vms -name "*.vbox" -exec VBoxManage registervm {} \;

# 05 May 2020 
	* Common npm start issues encountered max limit not set in linux. referer below article
		*https://github.com/gatsbyjs/gatsby/issues/11406
	
# 04 May 2020
	* CICD done.
	* Had to use nginx for serving react.
	* Jenkins agent setup had few issues so it took some time to solve it.
	* CD is ready.
	
# 03 May 2020
	* Installing Vagrant and Ruby from source.
	* autoconf and make funda.$ ./configure
	* Building from the source:-
		1) autoconf
		2) ./configure
		3) make
		4) make install
	* If deb is available use it
	* For partial installation use "apt --fix-broken install"
	* Setup ec2 production environment
	* used jenkins container for ci
	* installed ansible from source
	* setup ansbile and ec2 successfully.
	
# 02 May 2020
	* Created Env setup for the startup (React)

## 29 April 2020
	* Git branch name update and deletion
		Renaming an existing branch consists of following process:- 
			* git branch -m <NEW NAME>
			* git push origin -u <NEW NAME>
			* git push origin --delete <OLD NAME>

			1) Create a REPLICATE OF EXISTING BRANCH PUSH IT TO REPO.
			2) DELETE THE OLD BRANCH. 

## 21 April 2020
	* Connected MYSQL and C successfully probed multiple issues and noted them down.
	
## 20 April 2020
	* MYSQL Partial video by Giraffe acedemy.	

## 19 April 2020
	* C++ Complete video by Giraffe acedemy.	

## 18 April 2020
	* C programming Complete video of Giraffe academy.

## 17 April 2020
	* Basics of Makefile.
	* Created a simple tipper project in C.
	* Scanf issues resolved with https://stackoverflow.com/questions/26583717/how-to-scanf-only-integer
		* fgets() and strtol()

## 16 April 2020
	* Starting with C.
	* Starting with Basics of Linux Kernel.
	* Starting with Makefile.
	
	*Shortcuts discovered:-
		* Increasing font size within a terminal: * shift + ctrl ++ *
		* Reducing font size within a terminal: * ctrl -- *
	*Became isildur13


## 10 April - 15 April Break


## 9 April 2020
	* Issues with go provisioner.
		* Discovered that sleep command should be added after linking and then check for the availability of the binary.

	
## 8 April 2020

	* Vagrant issues with 2.0.2 unable to install disksize-manage plugin.
		* Don't blindly install packages using apt. Instead look at there website for new releases. 
>	* Vagrant box size could not be reduced to 5GB from default 10 GB need to inspect that..


## 7 April 2020:
	
	* vm management using vboxmanage for virtualbox vms. 
	* Vagrant issues relating to global-status vms.
	* Jenkins agent setup simple method of ssh discovered.
	* Created script for install go systematically.
	* Ensured that Go env stays stable and builds have no issues.

## 6 April 2020:
	
	* Developed a CD environment using jenkins agent for building and deploying build to respective environments.
	* Go build issues relating to CACHE definition.

## 5 April 2020:
	
	* Created Jenkins pipeline for CI.
	* Created sample provision scripts for vms creation 
-> Will make a template fot env setup..


## 4 April 2020:
	
	*
	*



## 3 April 2020:
	
	*
	*


## 2 April 2020:
	
	*
	*
