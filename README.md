# Fixed the following issue:
 - currently, sequelize-auto doesn't correctly infer enums by schema. If two identically-named enums exist in two different schema, then sequelize ends up merging them, leading to potentially incorrect items showing in the enum.

# How to fixed the issue:
 - install sequelize-auto 0.8.5\
   npm install sequelize-auto@0.8.5
 - use postgres.js & auto-builder.js  to override the old one in node_modules/sequelize-auto/lib/...

