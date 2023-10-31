# Make you of shared pipeline
Run the single shared pipeline for multiple projects and use the same variables.yml which includes all the parameters for projects.
In Azure DevOps, you can create a single pipeline that calls multiple pipelines or repositories using various approaches, depending on your requirements.
## varibale.yml
Creating a variables.yml file to store parameters for your YAML templates is a good practice and can help keep your pipeline YAML files clean and organized.
By centralizing your variables in a separate file, you can make changes to these parameters in one place, 
and all pipelines that use the variables will automatically reflect those changes.
Using a variables.yml file as demonstrated here allows you to maintain a central location for your common parameters and keep your YAML templates cleaner by passing these parameters when referencing the templates.
If you need to make changes to any of these common parameters, you can do so in a single place, making it easier to manage your pipelines.
