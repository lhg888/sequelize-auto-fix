# Fixed the following issue:
 - sequelize-auto doesn't correctly infer enums by schema. If two identically-named enums exist in two different schema, then sequelize ends up merging them, leading to potentially incorrect items showing in the enum.

# How to fixed the issue:
 - use postgres.js to override the old one in node_modules/sequelize-auto/...

