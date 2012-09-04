AtlasMusic search module for silver
===================================

This module extends Silver to search for music related data in Atlas. To use add the path to the module to the searchProviders entry in your config.js file and also add a section like this:

    AtlasMusicSearch: {
	apiKey: [Your API Key],
	limit: 50,
	timeout: 10000,
    },



