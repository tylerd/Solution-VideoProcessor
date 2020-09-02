# Video Processor Example Solution

Example video processing solution utilizing Azure Video Indexer, Logic Apps, and other Azure services

## Overall flow

1. Upload content to blob storage
2. Import content to Azure Video Indexer
3. Start processing content - wait for completion
4. Extract transcript
5. Generate Word document with captions
6. Upload Word document to SharePoint/OneDrive

## Related articles

* [Video Indexer API Docs](https://docs.microsoft.com/en-us/azure/media-services/video-indexer/video-indexer-use-apis)
* [Video Indexer Logic Apps Connector](https://docs.microsoft.com/en-us/azure/media-services/video-indexer/logic-apps-connector-tutorial)
* [Video Indexer Output JSON](https://docs.microsoft.com/en-us/azure/media-services/video-indexer/video-indexer-output-json-v2#root-elements-of-the-insights)
    ([transcript](https://docs.microsoft.com/en-us/azure/media-services/video-indexer/video-indexer-output-json-v2#transcript))
