1. Agent Product for youtube & gmail :
2. app -> __init__.py
2.1. functions:
   2.1.1.   def create_app()
   2.1.2. def home()
   2.1.3.def html()
   2.1.4. def health()
   2.1.5.def agent()
   2.1.6.Flask(__name__)
   2.1.7. CORS(app)
   2.1.8.app.register_blueprint()
   2.1.9. app.route()
   2.1.10. render_template()
   2.1.11.request.get_json()
   2.1.12.jsonify()
   2.1.13.str.strip()	
   2.1.14.dict.get()	
   2.1.15.str()
   2.1.16.Exception
4. app -> requirements.txt
3.1. packages:
   Flask 3.1.1	
   Gunicorn 21.0.0	
   Flask-CORS
5. app -> wsgi.py
4.1. functions:
   create_app()
6. app -> templates
7. app -> templates -> index.html
6.1. functions:
   $(id)	
   isGmail(command)	
   isYouTube(command)	
   processCommand(command)	
   showEmail(data)	
   playYouTube(data)
   document.getElementById()	
   new SR()	
   recognition.start()	
   classList.add()	
   classList.remove()	
   fetch()	
   response.json()	
   JSON.stringify()	
   Error()	
   console.error()
8. app -> youtube
9. app -> youtube -> __init__.py
8.1. functions:
   create_youtube_url(command)
   play()
   Blueprint()
   route()
   request.get_json()
   data.get()
   strip()
   jsonify()
10. app -> youtube -> player.py
9.1. functions:
   get_vid(query)
   create_youtube_url(command)
   urllib.parse.quote()	
   urllib.request.Request()	
   urllib.request.urlopen()	
   .read()	
   .decode()	
   re.findall()	
   re.search()	
   .lower()	
   .strip()	
   .group()	
   Exception	
   print
11. app -> gmail
12. app -> gmail -> __init__.py
11.1. functions imported:
   is_email_command()
   extract_email()
   generate_email_with_gemini()
   create_gmail_url()
13. app -> gmail -> gmail_gen.py
12.1. functions:
   generate_email_with_gemini(command)
   os.getenv()	
   urllib.request.Request()	
   json.dumps()	
   .encode()
   urllib.request.urlopen()	
   .read()	
   .decode()	
   json.loads()	
   re.sub()	
   re.search()	
   .group()	
   .strip()
   range()	
   time.sleep()	
   random.random()	
   RuntimeError()	
   Exception
14. app -> gmail -> gmail_write.py
13.1. functions:
   is_email_command(text)	
   extract_email(text)	
   create_gmail_url(subject, body, recipient)
