# Style and voice cheat sheet

Here's a cheat sheet that contains pointers about how to write technical articles for docs.microsoft.com services and technologies. These guidelines apply whether you are creating new documentation or updating existing documentation.

At a bare minimum, please:

- Spell check and grammar check your topics, even if you have to cut and paste into Word to do it.
- Use a casual and friendly voice--like you were talking to another person one-on-one.
- Use simple sentences. They are easier to understand, and they are more easily translated by both human and machine translators.

The following sections contain a more details:

+ [Use a customer-friendly voice]
+ [Consider localization and machine translation]
+ [Other style and voice issues to watch for]


##Use a customer-friendly voice

We aspire to follow these principles when we write technical content for docs.microsoft.com. We may not always get there, but we need to keep trying!

- **Use everyday words**: Try to use natural language, the words your customers use; be less formal but not less technical; provide examples that explain new concepts.

- **Write concisely**: Don't waste words and don't over explain. Be affirmative and don't use extra words or lots of qualifiers. Keep sentences short and concise. Keep your topic focused. If a task has a qualifier, put it at the beginning of the sentence or paragraph. Also, keep the number of notes to a minimum. Use a screenshot when it can save words.

- **Easy to scan**: Put the most important things first. Use sections to chunk long procedures into more manageable groups of steps (procedures with more than 12 steps are probably too long). Use a screenshot when it adds clarity.

- **Show empathy**: Use a supportive tone in the article, and keep disclaimers to a minimum. Honestly call out areas that will be frustrating to customers. Make sure the article focuses on what matters to the customer, don't just give a technical lecture.

##Consider localization and machine translation
Our technical articles are translated into many other languages, and some are modified for particular markets. People might also be using machine translation on the web to read the technical articles. So, write with the following guidance in mind:

- **Make sure the article contains no grammar, spelling, or punctuation errors**: This is something we should do in general. Markdown Pad 2.0 has a basic spell checker, but you should also paste the (rendered HTML) content from the article into Word, which has a more robust spell and grammar checker.

- **Make your sentences as short as possible**: Compound sentences or chains of clauses  make translation difficult. Split up sentences if you can do it without being too redundant or sounding weird. We don't really want articles written in unnatural language either.

- **Use simple and consistent sentence construction**: Consistency is better for translation. Avoid parentheticals and asides, and have the subject as near the beginning of the sentence as possible. Check out a few published topics - if the topic has a friendly, easy to read style, use it as a model.

- **Use consistent wording and capitalization**: Again, consistency is key. We use sentence casing for titles, so never capitalize a word if it isn't at the start of a sentence or a proper noun.

- **Include the "small words"**: Words that we consider small and unimportant in English because they are understood for context (such as "a", "the", "that", and "is") are crucial for machine translation - make sure you include them!

##Other style and voice issues to watch for

- Don't break up steps with commentary or asides.

- For steps that include code snippets, put additional information about the step into the code as comments. This reduces the amount of text people have to read through, and the key information gets copied into the code project to remind people of what the code is doing when they refer to it later.

- Use official product names, such as “Microsoft Intune” or "Microsoft Advanced Threat Analytics". Or you can just say “Intune” or "Advanced Threat Analytics".

- Don’t create acronyms in place of office product names, especially if they are not already established. For instance, don't use "Azure MS" in place of "Azure Mobile Services", or "AAD" in place of "Azure Active Directory". If an acronym is already established, such as "AD" spell it out on first reference with the acronym in parentheses ("Azure Active Directory (AD)"), then use "Azure AD" for subsequent references. Try to avoid acronyms in general though - they just confuse people.

- Use sentence casing for all titles.

- Use "sign-in" and not "log-in."

- Include the words "following" or "as follows" in every sentence that precedes a list or code snippet.

## Next steps

- Back to [contributors guide](./index.md)

<!--Anchors-->
[Use a customer-friendly voice]: #use-a-customer-friendly-voice
[Consider localization and machine translation]: #consider-localization-and-machine-translation
[other style and voice issues to watch for]: #other-style-and-voice-issues-to-watch-for
