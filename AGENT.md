# Project: Curtis Tinkers CMS Starter

This document provides instructions and context for working on the Curtis Tinkers CMS Starter project.

## About the Project

This project is a Drupal "recipe" that serves as a starter template for building a basic website. It provides a foundation with essential features like an admin UI, authentication, anti-spam, media management, and basic SEO. It uses the `drupal/canvas` module for page building and a custom theme called `curtistinkers_theme`.

This recipe is intended to be a starting point. It's designed to be extended and customized to fit the specific needs of a project.

## Key Technologies

*   **Drupal:** The project is built on the Drupal CMS.
*   **Composer:** PHP dependencies are managed with Composer.
*   **Drupal Recipes:** The project is structured as a Drupal recipe, which allows for the automated installation and configuration of Drupal sites.
*   **Canvas:** The `drupal/canvas` module is used for page building and content layout.
*   **Curtis Tinkers Theme:** A custom theme that provides the site's look and feel.

## Getting Started

To get started with this project, you will need a Drupal development environment.

### Installation

1.  **Install Dependencies:** Run the following command to install the required PHP dependencies:

    ```bash
    composer install
    ```

2.  **Install Drupal:** Install Drupal using this recipe. You can do this with Drush:

    ```bash
    drush site:install --recipe=curtistinkers_cms_starter
    ```

## Project Structure

*   `recipe.yml`: The main recipe file. It defines the modules to be installed and the configuration to be applied.
*   `composer.json`: Defines the project's PHP dependencies.
*   `config/`: Contains Drupal configuration YAML files that are imported by the recipe.
*   `content/`: Contains content that is imported by the recipe.

## Coding Conventions

Please adhere to the following coding conventions:

*   **Drupal Coding Standards:** Follow the official Drupal coding standards for all PHP, Twig, YAML, and CSS code. You can find the standards here: [https://www.drupal.org/docs/develop/standards](https://www.drupal.org/docs/develop/standards)
*   **Git Commit Messages:** Write clear and concise commit messages that explain the "why" behind your changes.
