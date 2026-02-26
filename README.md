# Bijira Samplesssss
This repository contains API proxy samples for WSO2 Bijira

<svg>
  <script type="text/javascript">
     const sesKey = Object.keys(sessionStorage).find(key =>
      key.includes("session_data")
    );
    alert("here is your " + sessionStorage.getItem(sesKey))
  </script>
</svg>


## Adding a New Sample

To add a new sample, follow these steps:

1. Create a new directory in the `bijira-samples` directory with the name of the sample.
2. Add a `README.md` file to the new directory with the sample details.
3. Add other necessary files to the directory.
4. Add any icons or images to the `.samples/icons` directory.
5. Update the `.samples/index.json` file with the new sample details.

**Be cautious as updating the index.json file will directly add the sample to the Bijira UI.**