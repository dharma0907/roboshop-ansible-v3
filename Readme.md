# we are creating roles in ansibles, roles are nothing but dividing the tasks and putting it under one folder instead of writing all together.
roles
   mongo
       tasks/ 
          main.yaml// will keep all roles here
        vars/
           will put all user data to pass
        files/
          will put all repo files here, like for mysql wee have some repo file to load 
        templates/
           will put templates section here like .j2
        handlers/
        meta/
          main.yaml
        defaults/
          main.yaml
        library/
        module_utils/
        lookup_plugins/