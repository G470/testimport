Chat Integration
================

You can easily integrate the public chat into a website. Just copy the code snippets from here. If you would like to make any adaptations, please modify the fields in the configuration widget. All changes are applied immediately to the snippet, so you can make your changes and copy the snippet to your clipboard afterwards. Please note that changes made on this page are not remembered.

Use this screen to generate the chat integration code. The chat integration configuration and snippet generator is available in the *Chat Integration* module of the *Chat* group.

To configure the chat and generate code snippet:

1. Select a pre-selected chat channel in the *Pre-selected channel* field.
2. Select a primary color for the chat design.
3. Customize the texts in the *Texts* section.

   .. figure:: images/chat-integration-configuration.png
      :alt: Chat Integration – Configuration

      Chat Integration – Configuration

   .. note::

      All changes made in the *Configuration* tab will not be saved. Every time you open this dialog, all fields will be reset to default values.

4. You can check the result in the *Preview* widget.

   .. figure:: images/chat-integration-preview.png
      :alt: Chat Integration – Preview

      Chat Integration – Preview

   .. note::

      The preview uses the real chat module. Other agents have to be available for chatting to preview all features. 

5. Copy the code snippet from the *Integration Code* widget and paste it into your website right before the ``</body>`` element.

   .. figure:: images/chat-integration-integration-code.png
      :alt: Chat Integration – Integration Code

      Chat Integration – Integration Code

If mixed content warning is displayed in the browser console, an administrator has to check that the system configuration setting ``HttpType`` is properly set. The website must run on the same protocol for chat widget to work.

For example, if the website is running OTRS on SSL, the system configuration option must be set to ``https``.
