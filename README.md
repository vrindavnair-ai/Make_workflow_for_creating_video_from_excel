# Make_workflow_for_creating_video_from_excel
This automation workflow using Make.com is used to create video using google veo for the topic entered on the excel sheet.
It contains the below module
1) Google sheet - watch row - it watches for the new topic and detailed explanation entered in the sheet.
2) Google vertex AI - uses gemini 2.5 flash to create the prompt for video generation using veo based on the detailed explanation from sheet.
3) Google vertex AI - create video module to create the video using the prompt genetaed by previous block
4) Youtube - To upload the video generated using veo directly to Youtube.
5) Google sheet - update row - to update the row with the prompt and the link of the video.
