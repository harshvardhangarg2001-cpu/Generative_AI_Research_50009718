# Generative_AI_Research_50009718
REIT6811 Applied Class 6 Group 1

Research project: **"Using Generative AI Tools - Boon or Bane"**
Repository maintained by student 50009718.

## Folder structure

Folders are separated into the following for document organisation:

| Folder | Contents |
|---|---|
| `Literature Review` | Journal and conference articles, books, newspaper articles |
| `Quantitative Analysis` | Survey data, survey questions, analysis files (Python scripts, csv, excel), survey analysis report |
| `Qualitative Analysis` | Interview transcripts, interview protocols, analysis and insights reports, data visualisations |
| `Drafts and Reports` | Draft research proposals, conference papers, final reports |
| `Additional Materials` | Information sheets, photos, other media files |

Two subfolders hold material that is deliberately kept out of version control -
see *Data access controls* below.

## Naming convention

Within each folder, documents are labelled using the following formula:

```
YYYYMMDD_NAME_V
```

Where V is the version number. An example is below:

```
20260912_Draft_0
```

Dating files this way means they sort chronologically rather than
alphabetically, the name says what the file is without opening it, and there is
no ambiguity about which version is current - the highest V wins, with Git
holding the full history behind it. There are no spaces or special characters in
file names, so the paths stay safe to script against and to move between
operating systems.

## Data access controls

Not all research data belongs in a shared repository. The following are
**excluded from version control** (see [`.gitignore`](.gitignore)) and stored in
**UQ Research Data Manager (RDM)** with access limited to the investigators
named on the ethics approval:

| Material | Why it is restricted |
|---|---|
| Signed consent forms | Carry participant names and signatures |
| Raw survey exports | May contain IP addresses, emails, identifying free text |
| Un-redacted interview audio and transcripts | Voice and content identify the speaker |

De-identified derivatives are what appear in this repository. Participants are
referred to as P01, P02, ... and the mapping back to real identities is held in
RDM, never here.

## Contributing

1. **Fork** this repository to your own GitHub account, then **clone** your fork
   in GitHub Desktop.
2. **Create a branch** with an informative name, e.g. `add-interview-protocol`.
   Do not commit directly to `main`.
3. **Make your change**, keeping each branch to one piece of work.
4. **Commit** with a message that says what changed and why - for example
   "Added cleaned survey data and initial analysis scripts", not "update".
5. **Push** the branch and open a **pull request** against `main`.
6. The repository owner reviews the pull request, resolves any merge conflicts,
   and merges it. Collaborators then **fetch origin** and **pull origin** so
   their local copy matches `main`.

Please do not commit anything listed under *Data access controls*.
