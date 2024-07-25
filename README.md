# 9anounGPT

9anounGPT is an AI Lawyer Assistant designed specifically for Tunisian law. It provides intelligent legal consultation and assistance through a sophisticated platform .

https://github.com/mrdaliselmi/9anounGPT/assets/75693386/c39858e7-d83c-41bc-a8af-6e01ecefee5d


## Key Features

The platform features:
- **A RAG-based AI chatbot** for personalized legal guidance
- **An authentication system** ensuring secure user access
- **A user forum** for community engagement
- **An appointment scheduling** system for convenient consultations
- **A notifications system** for timely updates

This project aims to make legal assistance more efficient, affordable, and accessible by integrating advanced technologies to enhance the accessibility and efficiency of legal services.

## Get started

### Installation:

```shell
git clone https://github.com/mrdaliselmi/9anounGPT.git
cd 9anounGPT
```

### Run locally:

```shell
docker-compose -f docker-compose.prod.yml up
```

### Development:

#### Start developing

```shell
git submodule init
git submodule update --remote --rebase
git submodule foreach --recursive git checkout dev
```
#### Add a submodule

```shell
git submodule add git@github.com:path_to/submodule.git <path-to-submodule>
```
## Project Components

### Backend

- **Chatbot Backend:** Handles the AI-powered chatbot for legal queries.
- **Forum Backend:** Manages the user forum for community interactions.
- **notification Backend (not included in the repository):** Manages the notifications system for timely updates.
- **Scheduling Backend (under developement):** Manages the appointment scheduling system for consultations.

### Frontend
Built with modern frameworks to provide a seamless user experience.
Components include the chatbot interface, forum pages, and scheduling system.

## Contribution

1. Fork the repository.
1. Create your feature branch (`git checkout -b feature/fooBar`).
1. Commit your changes (`git commit -am "✨ feat: add some fooBar"`).
1. Push to the branch (`git push origin feature/fooBar`).
1. Create a new Pull Request.

## Acknowledgments

We express our sincere gratitude to our supervisor, **Mr. Dhia Kandara**, for his invaluable guidance and support throughout this project. Special thanks to the members of the jury, **Mme. Assma Ben Hassouna**, and our team members, [Mehdi Cherif](https://github.com/mehdixlabetix), [Mohamed Ali Selmi](https://github.com/mrdaliselmi/), [Nour Eddine Ben Nejma](https://github.com/Lakhdher), and [Walid Sboui](https://github.com/walid192), for their dedication and hard work.

## Contact

For any inquiries, please contact:

- Mehdi Cherif: <a href="mailto:mehdi.cherif@insat.ucar.tn">Send email</a>
- Mohamed Ali Selmi: <a href="mailto:mohamedali.selmi@insat.ucar.tn">Send email</a>
- Nour Eddine Ben Nejma: <a href="mailto:noureddine.bennejma@insat.ucar.tn">Send email</a>
- Walid Sboui: <a href="mailto:walid.sboui@insat.ucar.tn">Send email</a>
