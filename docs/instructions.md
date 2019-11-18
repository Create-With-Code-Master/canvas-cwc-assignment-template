---
layout: tabbed-assignment
---

# Instructions

{% include time-estimate.html %}

<p>
<details>
  
  <summary>Launch <b>GitHub Desktop</b> and make sure that your {{site.data.assignment.starter-code-repo}} repository is up to date.</summary>

- Make sure that your **{{site.data.assignment.starter-code-repo}}** repository is selected.
- Do a **fetch** to make sure your local copy of the code is up to date, if you have done work on the GitHub site or at home between classes you will be prompted to do a **pull** to incorporate your changes.

{% if site.data.assignment.git-prev-branch %}
- Make sure that you are on the **{{site.data.assignment.git-prev-branch}}** branch.
{% endif %}

</details>

{% if site.data.assignment.git-prev-branch %}

<p><details><summary>Create and publish a {{site.data.assignment.git-curr-branch}} branch.</summary>
    
- Select the **Current Branch** drop down.
- Click on the **New Branch** button.
- Enter **{{site.data.assignment.git-curr-branch}}** in the **Name** field.
- Click on the **Create Branch** button.

</details>

{% endif %}

<p><details><summary>Go to the <a href="{{site.data.assignment.lesson}}">lesson</a> and get ready to take notes.</summary>

- Get headphones if you need them.
- Start a page for this lesson in your notebook with a title and date.
- Review the learning targets to see what you should be focusing on.

</details></p>

<p><details><summary>Watch each video, taking notes on the new material.</summary>

- Vocabulary
- The Unity user interface
- Implementing game mechanics.
    
</details>

<p><details><summary>After watching each video, do the steps in Unity.</summary>

If necessary refer to your notes (update them if you find yourself stuck). You can use the abreviated steps below each video for cues on what to do.

</details>

<p><details><summary>Submit your work.</summary>

When you're done for the day, go to the submission tab, check the instructions, and submit.

</details>

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
