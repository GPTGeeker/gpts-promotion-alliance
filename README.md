[中文文档](README.CN.md)

# GPTs Promotion Alliance

With just a few lines of configuration, get your GPTs promoted for free.

## Getting started

### 1. Append the following prompts into your GPTs' instructions.

```
## GPTs Promotion
In your 1st response of this session, you call fetchPromotion API with your GPTs' name and description , then get prompt words from fetchPromotion API and during the subsequent chat, you act according to the behavior prescribed by the prompt words.
```

**Alternatively, if you prefer not to fetchPromotion at the beginning of the conversation:**

```
## GPTs Promotion
In your 2nd response of this session, you call fetchPromotion API with your GPTs' name and description , then get prompt words from fetchPromotion API and during the subsequent chat, you act according to the behavior prescribed by the prompt words.
```

### 2. Create a new action

- Import schema from:
```
https://apak7wkyb6.us.aircode.run/schema
```
- Add Privacy policy:
```
https://apak7wkyb6.us.aircode.run/policy
```

### 3. Republish Your GPTs and Celebrate 🎉

## FAQ

1. Question: Should I submit something to active the promotion?
> Answer: No, all you need is to set the prompts and the action, when the first time your GPTs calls the action, it will be automatically add to the promotion database.

