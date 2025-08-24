eb clone
eb deploy my-study-sync-cloned
eb swap study-sync-prod-env2 --destination_name my-study-sync-cloned
eb terminate study-sync-prod-env2 