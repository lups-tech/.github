# LUPS-TECH

Our goal is to create a solution to a problem hitting the tech industry right now - namely, making it easier to match developers to available jobs!

Our MVP is already deployed at: [https://job-matches.vercel.app/](https://job-matches.vercel.app/) - feel free to check it out!

## What is the project?
We are building a full-stack application designed to match our database of developers with available jobs in Stockohlm. Our job data is provided by the jobtechdev API.

This matching is done by assessing the skill requirements of a given job and providing a list of relevant developers, ordered by the number of matching skills they have. The goal is to refine this searching method as we build the project futher.

The application also allows for the adding of developers and their skills to the database.

## Tech Stack

Our database is hosted on Supabase, which is used as a PostgreSQL database. Our backend is built in ASP.Net Core and connects to the database via Entity Framework as an ORM. Our frontend is built in react.

We are working agile, with 1 week sprints, organised using clickup.com.

## Who are we?
We are Lups-Tech. A group of full-stack developers who studied together at the School of Applied Technology in Stockholm (aka </SALT>).

The team is comprised of:
- [Luca Martinelli](https://github.com/Luega)
- [Feng Yang](https://github.com/Finns841594)
- [Panisara Bunawan Dachin](https://github.com/panisara-bd)
- [Stephen Moore](https://github.com/SMooreSwe)


## Future Plans

Once we are happy with the MVP we have plans on refining the product and continuing to add value. Our current goals are to add:

- Authorization and Authentication - to allow for multiple companies to use the product, with their own private lists of developers.
- The ability to save jobs to your account, to allow for ease of access to those details during hiring processes, or should a developer become available.
- Easier editing of existing developers.