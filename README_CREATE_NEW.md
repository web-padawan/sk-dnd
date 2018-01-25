### Creating a new Vaadin Element

1. Clone this repo

        git clone git@github.com:vaadin/sk-dnd-skeleton.git new-element-name

2. When in the `new-element-name` folder, replace all `sk-dnd` and `SkDnd` ocurrences with your new element name.

        perl -pi -e 's,sk-dnd,new-element-name,g' *.* demo/* test/*
        perl -pi -e 's,SkDnd,NewSkDndName,g' *.* demo/* test/*

3. Rename the element

        mv sk-dnd.html new-element-name.html

4. Check that everything works all right

        npm install
        bower install
        polyserve

  And check that everything works:
  
  - http://localhost:8080/components/new-element-name/index.html
  - http://localhost:8080/components/new-element-name/demo/index.html
  - http://localhost:8080/components/new-element-name/test/index.html

5. Remove this README file sinde it is not needed any more.

        rm README_CREATE_NEW.md

5. Finally, initialize git so as we have an empty history for our `<new-element-name>`

        rm -rf .git
        git init
        git add * .??*
        git commit -m 'First Commit' -a

