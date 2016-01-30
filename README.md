|[![The HYIP Project](https://avatars1.githubusercontent.com/u/8466209?v=10&s=20)](https://github.com/hyip) |This [repo](https://github.com/hyip/info "Repository") is courtesy of [The HYIP Project](https://github.com/hyip/monitor "High Yard Investment Program"). Find all of them on [The Project Map](https://github.com/hyip/info/wiki/maps#project-map "Project Mapping").|[![The HYIP Project](https://tophyipmonitor.files.wordpress.com/2015/06/cow.png?w=20)](https://tophyipmonitor.wordpress.com/hyip-business/nature-1/#main) |
|:----|----|----:|{|

# hyipinfo.github.io
Information Flow System

This project section is running on Amazon Web Service (AWS) using AWS CodeDeploy. Please refer to the tutorial:
http://docs.aws.amazon.com/codedeploy/latest/userguide/github-integ-tutorial.html#github-integ-tutorial-deploy

Important Checklist:
* [Install, Uninstall, or Reinstall the AWS CodeDeploy Agent](http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-run-agent.html#how-to-run-agent-install-linux)
*  [Add an AppSpec File](http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-add-appspec-file.html) and [AppSpec File Reference](http://docs.aws.amazon.com/codedeploy/latest/userguide/app-spec-ref.html)
* [Deploy a Revision](http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-deploy-revision.html) and [GitHub Authentication](http://docs.aws.amazon.com/codedeploy/latest/userguide/github-integ.html#github-integ-behaviors-auth)
* [Create a Service Role](http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-create-service-role.html) and [Setting Up](http://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-create-service-role.html)
* [General Troubleshooting](http://docs.aws.amazon.com/codedeploy/latest/userguide/troubleshooting.html#troubleshooting-checklist)


Push Command:
```
aws deploy push \
  --application-name WordPress_App \
  --description "This is a revision for the application WordPress_App" \
  --ignore-hidden-files \
  --s3-location s3://codedeploydemobucket/WordPressApp.zip \
  --source .
```


***
|[:arrow_backward:](https://github.com/hyip/info) [Prev](https://github.com/hyip/info)|[Next](https://github.com/hyipinfo/hyipinfo.github.io/wiki/Home) [:arrow_forward:](https://github.com/hyipinfo/hyipinfo.github.io/wiki/Home)|
|:----|----:|
