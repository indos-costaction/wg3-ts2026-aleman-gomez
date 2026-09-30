# Practical Session: Setup Instructions

Please complete **all** of the steps below **before** the practical session. Some downloads are large and can take a while, so don't leave this until the last minute.

---

## 1. Clone the course repository

Open a terminal and move to the folder where you want to keep the course material. We recommend a folder inside your **home directory**, so that it is visible from Neurodesk later (see step 2).

```bash
cd ~                      # or any folder inside your home directory
git clone https://github.com/indos-costaction/wg3-ts2026-aleman-gomez.git
cd wg3-ts2026-aleman-gomez
```

> **No `git`?** Install it first (e.g. `sudo apt install git` on Ubuntu/Debian, or from <https://git-scm.com/downloads> on macOS/Windows).

---

## 2. Install the Neurodesk App (**mandatory**)

The practical session runs entirely inside **Neurodesk**, which provides all the neuroimaging software we will use. Installing it is **mandatory**.

1. Go to the Neurodesk website: <https://www.neurodesk.org>
2. Download and install the **Neurodesk App** for your operating system, following the official installation guide.
3. Launch the app once to make sure it starts correctly.

### Where are my files inside Neurodesk? (Linux)

On Linux, Neurodesk mounts your **home directory** at **`/data`**. Inside it, Neurodesk creates a folder called **`neurodesk-storage`**.

| On your computer        | Inside Neurodesk               |
|-------------------------|--------------------------------|
| `~` (your home folder)  | `/data`                        |
| —                       | `/data/neurodesk-storage`      |

So, if you cloned the repository in your home directory, you will find it inside Neurodesk at:

```
/data/wg3-ts2026-aleman-gomez
```

---

## 3. Download the dataset

Once the repository is cloned **and** Neurodesk is installed:

1. Open Neurodesk.
2. Navigate to the cloned repository and open the **`HandsOn`** folder.
3. Open **any** of the notebooks in that folder.
4. Run the cell **`0.1 Dataset: Downloading the dataset`**.

This downloads the data needed for the practical session. Wait until the cell finishes without errors.

---

## Checklist

Before the session, make sure that:

- [ ] The repository `wg3-ts2026-aleman-gomez` is cloned on your computer.
- [ ] The Neurodesk App is installed and starts correctly.
- [ ] You can see the repository from inside Neurodesk.
- [ ] Cell **0.1 Dataset** has been run and the dataset downloaded successfully.

If you run into any problems, please get in touch **before** the session so we can solve them in advance.
