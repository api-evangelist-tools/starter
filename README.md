# Starter
This is  repository for a starter API governance editor that uses the Monaco editor and Spectral rules to make for a standlone solution you can use to lint OpenAPI specifications using Spectral rulesets.

This is a build -- if you want the full solution you can grab [the base solution I have forked from the Italian Government](https://github.com/italia/api-oas-checker/blob/master/README.en.md). It is one of the slickest client-side approach to using Spectral rules and governance I have seen, and I recommend looking at the [API Starter Pack](https://github.com/teamdigitale/api-starter-kit) produced by the Italian government.

## Usage
There are three ways in which you can put this editor to work as part of your API governance depending on your skills, needs, and resources you have available. 

1. **Web** - You can visit the GitHub Pages portion of this repository and use the editor. It is completely client-side with no backend, and OpenAPI or no other data is stored -- it is stateless.
2. **Fork** - You can fork this repository and fire up in your own cloud or on-premise edition of GitHub and publish with GitHub Pages-- then you can just edit the ruleset.json to customize rules, and you can set the default OpenAPI using initial.yaml. 
3. **Build** - If you have the resources and skills I highly recommend building on the same base that I did and fork the [OpenAPI Checker from the Italian government](https://github.com/italia/api-oas-checker/blob/master/README.en.md). You will get more capabilities out of the box, their version of rules, and allow you to customize better for your needs.

## Support
If you have any questions just leave an issue on this repository or feel free to email [info@apievangelist.com](mailto:info@apievangelist.com) with any questions.
