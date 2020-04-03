# General

## Goals: 
1. Clean questions database with score for each question 
2. Questionaires database. 
   - One Master Questionaire (for further usage in apps etc.)
   - Create other Questionaire (based on the same questions with additional ones)
2. Providing the Translation for all questions. 

## Secondary Targets
1. Collecting Anonymous questionaire results 
2. Linking the questionnaire result to a clinical result (positive/negative)



## Notes
GET Request: 
return the translation-key, no language preference
with url or path parameter `language` questionaire with the translation should be returned


PUT POST etc. Requests 
(for now) Should only be posted in English 
- translation keys will be automatically generated, the english sentences will be used to update the translation file (also as additional nodes) 

