## README

Dummy app to check customisation of admin:scaffold_controller templates.

### to check

run into console:
```
rails g admin:scaffold_controller foo bar
```

it should generate correct templates for all pages except index.
Index(app/views/admin/foos/index.html.erb) should contain dummy content:
```
index.html.erb.erb
```
