#Cloud Foundry Angular Example

This is one of three projects referenced by https://github.com/spring-projects/spring-security-oauth/issues/1676
1) https://github.com/smitchell/cloud-foundry-angular-example
2) https://github.com/smitchell/spring-boot-netflix-zuul-proxy
3) https://github.com/smitchell/spring-security-5-upgrade_sso-auth-server

You need to know the route of each project to make this example work. 
First, push all three project to your test space so that Cloud Foundry assigns each a route, 
then uncomment the routes section of all three project's manifest.yml files and set it to 
the corresponding route that was assigned.

Next, follow the instructions in the Proxy and Auth Service README.md file instructing you where to set
the routes in those two projects.

### How to push cloud-foundry-angular-example to Cloud Foundry

1) `cf login` or `cf t -s [space name]` to point to a test space.
2) Run `ng build --prod`. 
3) `cf push` to deploy to your test space.


