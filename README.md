# ccf-hca-rui-locations
Repo for refining the HCA RUI Locations

## Updating the rui locations

After either editing the defaults in `create-rui-locations.js` or adding/editing rui registration json files in the rui_registrations folder, run

```bash
node create-rui-locations.js
```

to regenerate the `rui_locations.jsonld` file. Commit and push the change and it will be reflected at <https://cns-iu.github.io/ccf-hca-rui-locations/>.
