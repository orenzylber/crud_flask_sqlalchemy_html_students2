# Very good flask template
## contains:
### sqlalchemy
### CORS
# simple example

##### live site
# on netlify
#https://idyllic-froyo-8cefa8.netlify.app/
# on github
#https://orenzylber.github.io/crud_flask_sqlalchemy_html_students2/


# Update DB create 
    with app.app_context():
        db.create_all()
        app.run(debug=True)

# Run:
    create a virtual enviroment
    py -m virtualenv env
# activate:
    env\script\activate
# prepare the environment
    pip install -r .\requirements.txt
    flask run