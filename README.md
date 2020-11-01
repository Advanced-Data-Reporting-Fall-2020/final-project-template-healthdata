# North Carolina Local Health Department Expenditures

Created by Christian Avy, Rachel Crumpler, Dominick Ferrara and Jamie Krantz

## Project goal

In this project, we are tracking expenditures for local health departments in North Carolina and discussing what they can tell us about each county's preparedness for COVID-19 and other epidemic or pandemic level threats.

## Project notes

### Staff involved

Chrstian Avy: cavy@live.unc.edu

Rachel Crumpler: rachel22@live.unc.edu

Dominick Ferrara: dferrara@live.unc.edu

Jamie Krantz: jakrantz@live.unc.edu

### Data sources

To collect data, we sent out public records requests to every local health department in North Carolina, requesting expenditure data. We heard back from more than 50 of them. Population data was retrieved from the U.S. Census Bureau and the North Carolina Office of State Budget and Management. Our collected data is available in a compiled Google Sheet.

## Technical

An outline of the basic project structure is available at https://github.com/associatedpress/cookiecutter-r-project

### Project setup instructions

After cloning the git repo:

`datakit data pull` to rerieve the data files.

Open `new-project.Rproj` in RStudio.

## Data notes

Our data set does not include revenues for each local health department. This data can be found in counties' annual audits, which can often be found on the counties' websites.

A limitation to the story is that the state does not track each county's expenditures. Instead, they only track spending on specific state-backed programs. Additionally, the state does not list how much money goes to each county. The state budget includes a line item for how much total money is headed towards counties, but not divided by county.
