# Greater Seattle Linux User Group website.  
View it live at [https://gslug.org](https://gslug.org)

## To Make Changes To gslug.org

1. Fork this repository.
1. Make a local clone of the fork.
    ```
    git clone git@github.com:<yourname>/gslug.git
    ```
1. Work in the local clone `cd gslug`
1. Install the required ruby gems to the local directory.
    ```
	bundle install --path vendor/bundle
    ```
1. Run jekyll to start a local server.
    ```
	bundle exec jekyll serve 
    ```
1. At this point you can view the website locally in your browser. 
    ```
	localhost:4000
    ```
1. Make changes and test in the local clone.
1. Push the changes to github
    ```
    git push origin master
    ```
1. Request a merge of your new branch back to this repository.
