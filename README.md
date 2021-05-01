# fetch_api_project
VanillaJS project that can fetch data from .txt file, .json file or from an external API source (github API) 

1/5/21 - Fixed error handling for fetch text. Fetch does not throw errors for 404s, that is why you need to manually check for errors, and then throw it manually.
