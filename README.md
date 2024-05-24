# Crypto Knowledge Source Tracker

This repository contains two CSV files used for building a comprehensive crypto knowledge base. These files are managed and updated through GitHub PRs and issues. The content is utilized for large language model (LLM) based applications.

## CSV Files

### 1. `knowledge_source_tracker.csv`
This file tracks all the sources or URLs that can be crawled to build a crypto knowledge base, including blogs, research portals, Twitter handles, project documentations, media houses, and GitHub repositories.

#### Schema:
- **Source Name**: The name of the source.
- **Source Type**: The type of the source (e.g., Blog, Research Portal, Twitter Handle, Project Docs, Media House, GitHub Repo).
- **URL**: The URL of the source.
- **Description**: A brief description of the source.
- **Tags**: Relevant tags for easier searching and filtering.

#### Example:
| Source Name      | Source Type     | URL                                     | Description                                   | Tags                             |
|------------------|-----------------|-----------------------------------------|-----------------------------------------------|----------------------------------|
| CoinDesk         | Media House     | https://www.coindesk.com                | Leading media platform for crypto news        | News, Media House, Blockchain    |
| Decrypt          | Media House     | https://decrypt.co                      | Media site for crypto news and analysis       | News, Media House, Crypto        |
| VitalikButerin   | Twitter Handle  | https://twitter.com/VitalikButerin      | Twitter account of Ethereum co-founder        | Social Media, Twitter, Ethereum  |
| Ethereum Docs    | Project Docs    | https://ethereum.org/en/developers/docs/| Official documentation for Ethereum           | Project Documentation, Ethereum  |
| Uniswap          | GitHub Repo     | https://github.com/Uniswap/uniswap-v2-core | GitHub repository for Uniswap V2 core code | Development, Open Source, GitHub |
| A16Z Crypto Blog | Blog            | https://a16zcrypto.com/research/        | Blog by Andreessen Horowitz on crypto research| Blog, Research, Venture Capital  |

### 2. `tags.csv`
This file contains a list of predefined tags that can be used to categorize and tag the sources in the `knowledge_source_tracker.csv` file.

#### Schema:
- **Tag**: The name of the tag.
- **Description**: A brief description of what the tag represents.

#### Example:
| Tag            | Description                                      |
|----------------|--------------------------------------------------|
| Blockchain     | Related to blockchain technology                 |
| Crypto         | General cryptocurrency-related content           |
| News           | News and updates                                 |
| Blog           | Blog posts and articles                          |
| Research       | Research-related content                         |
| Academic       | Academic papers and research                     |
| Portal         | Online portals                                   |
| Social Media   | Content from social media platforms              |
| Analyst        | Analysis and commentary                          |
| Twitter        | Content from Twitter                             |
| Project Documentation | Documentation for specific projects      |
| Media House    | Content from media houses                        |
| Development    | Development-related content                      |
| Open Source    | Open source projects and repositories            |
| GitHub         | Content from GitHub                              |
| Podcast        | Podcast episodes                                 |
| YouTube        | YouTube videos                                   |
| Education      | Educational content                              |
| Technology     | Technology-related content                       |
| Finance        | Finance-related content                          |
| Bitcoin        | Related to Bitcoin                               |
| zkSync         | Related to zkSync                                |
| Memecoin       | Related to memecoins                             |
| DeFi           | Decentralized Finance                            |
| Aave           | Related to Aave                                  |

## Contribution Process

To add new sources or tags, please follow the process outlined below:

### Step 1: Create an Issue
- Open an issue describing the new source or tag you want to add.
- Include all relevant details such as the source name, type, URL, description, and tags.

### Step 2: Fork the Repository
- Fork this repository to your GitHub account.

### Step 3: Update the CSV
- Clone your fork to your local machine.
- Open the `knowledge_source_tracker.csv` or `tags.csv` file.
- Add the new source or tag following the schema described above.
- Commit your changes with a descriptive commit message.

### Step 4: Create a Pull Request (PR)
- Push your changes to your fork on GitHub.
- Create a pull request (PR) from your fork to the main repository.
- Link the PR to the issue you created earlier.

### Step 5: Review and Merge
- The maintainers will review your PR.
- Once approved, your changes will be merged into the main repository.

## Usage in LLM-Based Applications

The content in these CSV files is used to feed large language models (LLMs) with structured and comprehensive crypto knowledge. By maintaining a diverse and up-to-date list of sources, we ensure that the LLMs can access accurate and relevant information. This helps in generating more accurate and insightful responses in various crypto-related applications, such as chatbots, research assistants, and more.
