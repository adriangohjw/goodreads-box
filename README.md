<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/4597409/90305251-2bb62d00-def3-11ea-9280-cde379107331.png">
  <h3 align="center">goodreads-box</h3>
  <p align="center">Update a pinned gist to show your currently reading books and progress on Goodreads</p>
</p>

---

> 📌✨ For more pinned-gist projects like this one, check out: https://github.com/matchai/awesome-pinned-gists

## Setup

### Prep work

1. Create a new public GitHub Gist (https://gist.github.com/), you can type any random content as placeholder, it will be replaced automatically.
1. Create a token with the `gist` scope and copy it (https://github.com/settings/tokens/new?scopes=gist&description=goodreads-box).
1. Create a Goodreads account (https://www.goodreads.com/user/sign_in).
1. Create Goodreads App and copy the Api Key (https://www.goodreads.com/api/keys).

### Project setup

1. Fork this repo.
1. Go to the repo Settings > Secrets.
1. Add the following environment variables:
  - **GOODREADS_API_KEY**: The Goodreads App Api Key.
  - **GOODREADS_USER_ID**: Your Goodreads account id, can be found in the profile page url e.g. `https://www.goodreads.com/user/show/`**118339107**`-mdluo`
  - **BOOKS_SORT_BY**: Optional, default value is `date` which means sort books by update time. Another valid value is `percent`, sort book by read percentage.
  - **GH_TOKEN**: The GitHub token generated above.
  - **GIST_ID:** The ID portion from your gist url: `https://gist.github.com/mdluo/`**`f890a4d178012c5a3c5c29ff743a84e8`**.
