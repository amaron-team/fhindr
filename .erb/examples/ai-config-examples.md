# AI configuration examples

Below are some example configurations for the most well known vendors, please note that several vendors will use the OpenAI API format.
This will be specified in the vendors' documentation. If this is the case just select OpenAI as the format to use, regardless of the vendor.
For example, Deepseek uses the OpenAI API format, so you will have to set it to OpenAI format even though the Deepseek models aren't from OpenAI.

## OpenAI

**Model name:** gpt-4o-mini <br>
**API format:** OpenAI <br>
**API endpoint:** https://api.openai.com/v1/chat/completions <br>
**API key:** Can be bought from: https://platform.openai.com/api-keys <br>

More info: https://openai.com/

## Google

**Model name:** gemini-2.5-flash <br>
**API format:** Google <br>
**API endpoint:** https://generativelanguage.googleapis.com/v1beta/models/ <br>
**API key:** Free keys can be acquired from: https://aistudio.google.com/apikey

More info: https://ai.google/

## Cloudflare

**Model name:** llama-3-8b-instruct <br>
**API format:** Cloudflare <br>
**API endpoint:** https://api.cloudflare.com/client/v4/accounts/**<=accountId=>**/ai/run/@cf/meta/ <br> => Attention, for Cloudflare-hosted models you will need to include your account id in the endpoint.
You can retrieve your account id from their website.<br>
**API key:** Free keys can be acquired from: https://dash.cloudflare.com/profile/api-tokens

More info: https://ai.cloudflare.com/

## Deepseek hosted by NVIDEA

**Model name:** deepseek-ai/deepseek-r1 <br>
**API format:** OpenAI <br>
**API endpoint:** https://integrate.api.nvidia.com/v1/chat/completions <br>
**API key:** Free keys can be acquired from: https://build.nvidia.com/settings/api-keys <br>

More info:
 - https://build.nvidia.com/
 - https://www.deepseek.com/en

## Local LLM using Ollama

**Model name:** llama3.1 <br>
**API format:** Ollama <br>
**API endpoint:** http://localhost:11434/api/chat/ <br>
**API key:** No API key required

More info: https://www.ollama.com/
