# projects
		This is just a git project to hold my various projects. Some of these project have been started others are very much a work in progress, and others haven't really been started other then the idea is written here.
## LinkedIn/Articles Medium(some may have video tie in)
		*Why Startups should consider Grails 3.x
		*ACL is dead
		*Gorilla Guide to introducing Groovy to Java developers.
		Why your full stack developers, aren't really full stack.
		Abstraction/Over Engineering Rant
		Should everyone learn to program / code...no, however...
		Is a college education worth it... yes, however...
		Software Engineering/Programing Art or Science
			idea marination
			thinking 
			
## Android Groovy
### Hello world
###Restaurant Quest
		an action adventure game based on exaggerations of stories, rumors, and gossip, from when I worked at the Ground Round
		A Fashion App based on an idea from Alexandra.
## SE GEEK Videos(use dgeneartor as an example)
		Grails structure
		Grails configuration
		Domain Objects
		Controllers
		Services

		Abstraction Rant
		Groovy Gorilla tactics
		Building Your own AST transforms
		Groovy SQL
		Groovy DSL
		Command line
## Grails Plugins
### Enforcer
		upgrades and maintenance
### HTML Enforcer
		Grails plugin to enforce rules for html that can be stored
		Based off https://github.com/owasp/java-html-sanitizer
		Use Groovy maps for config(consider a dsl)
		Use JSOUP for the base
### MultiFactorAuth
		Grails plugin supporting the tie in of extra forms of authentication
			email
			text
			totp
			etc
		based off:
			http://www.gobloomhealth.com/multi-factor-authentication-part-1/
			http://www.gobloomhealth.com/multi-factor-authentication-part-2/
			https://github.com/osoco/grails-spring-security-otp
### HasManyAlternative
		Grails plugin that provides an alternative to the gorm hasmany for performance
		AST annotation may be similar in it's delegation to Enforcer. Service deals with transactions and caching ids
		AST adds adds a getMethod, addMethod, addList, removeMethod removeAll
		Annotation takes bean name of the other domain class

		May used traits and services

## Grails App
	DGenerator Grails 3 sample app
		Documentation
		Domain classes
			user
				name
				email
				avatar
			role
				name
			userRole
				userId
				roleId
			project
				name
			projectTemplate
				projectId
				templateId
			objectRole
				id
				role
				objectId
				objectClass
			template
				template(document json)
				connectionId nullable
				isSample
				not editable just copyable
			output
				name
				host/fileLocation(with extension)
				port
				userName
				password
				isDB
				driver/service(could be file service)
		Ember/Angular app?
		BootStrap/less
		Security XSS
		Spring security
		rule  Service
		Template editor
		Template management
		Generator DSL
		Connections editor
		Job editor
		Template job runner Quartz
		Job status page / management

##  Infrastructure setup
		Git Lab/ci
		Tomcat
		Artifactory
		Elastic Search
