# Bino.io - The Binoio Family of Apps

Welcome to the public repository for [bino.io](https://bino.io). This site showcases our portfolio of apps, provides information about our philosophy, and features our blog.

## Developer Workflow

1.  Make changes to the site in the `main` branch.
2.  Commit and push your changes.
3.  GitHub Actions will automatically build the Jekyll site and push the generated HTML to the `deploy` branch.

## Self-Hosting Directions

To host the site on your own server, follow these steps to pull the latest generated site:

1.  **Initial Setup (First time only):**
    ```bash
    # Clone the repository
    git clone https://github.com/binoio/bino.io.git /var/www/bino.io
    cd /var/www/bino.io

    # Fetch all branches
    git fetch origin

    # Switch to the 'deploy' branch where the generated HTML lives
    git checkout deploy
    ```

2.  **Update the site (Whenever you push to main):**
    On your server, run the following command to pull the latest generated HTML:
    ```bash
    cd /var/www/bino.io
    git pull origin deploy
    ```

Ensure your web server (e.g., Nginx or Apache) is configured to serve files from the `/var/www/bino.io` directory.

## About the Binoio Family

Explore our portfolio:
- Edith
- Outsight
- Kona
- Atmo
- Donots
- ManoScroll
- Note Enough

Visit [bino.io/about](https://bino.io/about) for more details.
