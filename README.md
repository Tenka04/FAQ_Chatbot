# Intern-F Chatbot

Intern-F Chatbot is a FAQ chatbot designed to assist users with information about internships, application processes, and company details for Micro Information Technology Services.

## Demo

Try it live: [Intern-F Chatbot Demo](https://tenka04.github.io/FAQ_Chatbot/)

## Features

- Answers questions about internship opportunities, application procedures, and company information.
- Provides contact details and keeps the conversation ongoing.
- Built using Dialogflow intents and integrated with a web interface.

## Project Structure

```
.gitattributes
agent.json
index.html
LICENSE
package.json
README.md
intents/
  application.process_usersays_en.json
  application.process.json
  company.info_usersays_en.json
  company.info.json
  contact.details_usersays_en.json
  contact.details.json
  Default Fallback Intent.json
  Default Welcome Intent_usersays_en.json
  Default Welcome Intent.json
  internship.apply_usersays_en.json
  internship.apply.json
  internship.details_usersays_en.json
  internship.details.json
  keep.conversation.ongoing.json
```

- **index.html**: Main web page embedding the Dialogflow Messenger chatbot.
- **intents/**: Contains all Dialogflow intent definitions and user example phrases.
- **agent.json**: Dialogflow agent configuration.
- **LICENSE**: MIT License.
- **package.json**: Project metadata.
- **README.md**: Project documentation.

## Usage

1. Open `index.html` in a web browser.
2. Interact with the chatbot to get information about internships, application processes, and more.

## Customization

- To update chatbot responses or supported questions, edit the JSON files in the `intents/` directory.
- To change the chatbot appearance, modify the CSS in `index.html`.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Developed by Sujal Sangle**