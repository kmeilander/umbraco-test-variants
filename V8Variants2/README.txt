https://our.umbraco.com/documentation/Getting-Started/Backoffice/Variants/


NOTES:
- Each page can have a uniqe page name, and differnt URLs, but then they share the node ID.
-- this means you should be able to do slight variations in content, as long as the overall structure will be the same

- Dictionary items hidden in translation section
-- Need to expliscitly give userrs acccess to this section, cuz it looks like there's nothing else there

- To fallback to default language, get value like @Model.Value("marqueeHeadline", fallback: Fallback.ToLanguage)
--- Not sure if you can fall back using the Model Builder

- node.IsVisible() doesn't seem to work with variance, not sure if this is a bug or not. 
--- use node.IsPublished() instead


Umbraco User:
user@glg.com
Password1234