# Very good flask template
## contains:
### sqlalchemy
### CORS
# simple example

##### live site
# on netlify
https://prismatic-centaur-f28a5d.netlify.app/
# on github



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