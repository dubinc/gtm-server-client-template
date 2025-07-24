# Dub Server Client Template for Google Tag Manager

A server-side client template for Google Tag Manager that receives conversion tracking events from web containers. This template validates incoming requests, parses query parameters, and structures event data for both lead and sale conversions.

## Configuration Parameters

### Request Path
- **Name**: `expectedPath`
- **Type**: Text
- **Default**: `/dub-tracking`
- **Description**: The path where this client will listen for incoming requests from the web container. Must start with a forward slash (/).

### Debug Logging
- **Name**: `enableLogging`
- **Type**: Checkbox
- **Default**: false
- **Description**: Enable detailed logging to help debug conversion tracking issues. Should be disabled in production for better performance.

See the detailed instructions in the [documentation](https://docs.dub.co/docs/gtm-server-client-template).