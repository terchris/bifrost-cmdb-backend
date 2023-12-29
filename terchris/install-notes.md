
# Install Notes

yarn create strapi-app bifrost-cmdb-backend --ts
yarn create v1.22.21
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...

success Installed "create-strapi-app@4.16.2" with binaries:
      - create-strapi-app
? Choose your installation type Custom (manual settings)
? Choose your default database client postgres
? Database name: bifrost
? Host: 127.0.0.1
? Port: 5432
? Username: strapi
? Password: ********
? Enable SSL connection: No

Creating a project with custom database options.
Creating a new Strapi application at /Users/terchris/learn/projects-2024/bifrost-cmdb-backend.
Creating files.
Dependencies installed successfully.
Initialized a git repository.


Your application was created at /Users/terchris/learn/projects-2024/bifrost-cmdb-backend.

Available commands in your project:

  yarn develop
  Start Strapi in watch mode. (Changes in Strapi project files will trigger a server restart)

  yarn start
  Start Strapi without watch mode.

  yarn build
  Build Strapi admin panel.

  yarn strapi
  Display all available commands.

You can start by doing:

  cd /Users/terchris/learn/projects-2024/bifrost-cmdb-backend
  yarn develop

✨  Done in 365.97s.

yarn develop
yarn run v1.22.21
$ strapi develop
⠋ Building build context
⠙ Building build context[INFO] Including the following ENV variables as part of the JS bundle:
    - ADMIN_PATH
    - STRAPI_ADMIN_BACKEND_URL
    - STRAPI_TELEMETRY_DISABLED
✔ Building build context (125ms)
✔ Creating admin (11190ms)
⠼ Loading Strapi[2023-12-29 11:54:22.368] info: The Users & Permissions plugin automatically generated a jwt secret and stored it in .env under the name JWT_SECRET.
✔ Loading Strapi (4409ms)
✔ Generating types (668ms)
✔ Cleaning dist dir (9ms)
✔ Compiling TS (2019ms)

 Project information

┌────────────────────┬──────────────────────────────────────────────────┐
│ Time               │ Fri Dec 29 2023 11:54:25 GMT+0100 (GMT+01:00)    │
│ Launched in        │ 7105 ms                                          │
│ Environment        │ development                                      │
│ Process PID        │ 56825                                            │
│ Version            │ 4.16.2 (node v20.10.0)                           │
│ Edition            │ Community                                        │
│ Database           │ postgres                                         │
└────────────────────┴──────────────────────────────────────────────────┘