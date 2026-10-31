# Repository agent instructions

## Questions and chat communication

- Ask all questions in the actual chat conversation.
- Never open a Codex pop-up chat, question dialog, option picker, onboarding
  panel, or separate input window to ask for clarification, preferences,
  permission, or confirmation.
- Do not use `request_user_input`, `request_user_input_async`,
  `request_onboarding_input`, `request_option_picker`, or
  `request_environment_input` to ask questions. Write a normal chat message
  instead and wait for the user's reply when an answer is required.


## Browser and computer-use policy

- Do not use the `computer-use` skill, native desktop automation, or native
  mouse/keyboard control unless the user explicitly requests that method.
- For websites and web applications, use ChatGPT/Codex's built-in browser and
  browser tools instead.
- A request to inspect a dashboard, screenshot, or website does not authorize
  the computer-use skill or native desktop control.
- If the built-in browser cannot complete the task, explain the limitation in
  normal chat. Do not fall back to computer use without an explicit user request.
