# Module Federation Test

The parent for the module federation test

## Setup

Clone the following repos into this one:

* https://github.com/devbucket/module-federation-shell
* https://github.com/devbucket/module-federation-profile

Then create an `.env` from the `.env.dist`

The run `yarn install` from the root here. The project uses yarn workspaces.

## Running all

To run the projects in parallel, you run `yarn start` from the root.

## Running individually

Run the individual projects with `yarn start` inside the project's folder.
