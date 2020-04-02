---
title: Subjects
nav: true
table-id: "#subjects"
table-paginate: true
---
{% assign subjects = site.data.argo_subjects_filtered %}
 
The table below lists terms used in the existing Argonaut "subject" field.
This will give you an idea of the types of terms that are applied.
Using the same terms listed here will help users find related content across issues.
Search and sort to find related terms.

<table id="subjects" class="table table-striped">
    <thead>
       <tr>
          <th>Subject</th>
          <th>Count</th>
       </tr>
    </thead>
    <tfoot>
       <tr>
          <th>Subject</th>
          <th>Count</th>
       </tr>
    </tfoot>
    <tbody>
    {% for s in subjects %}
    <tr>
       <td >{{ s.subject }}</td>
       <td >{{ s.count }}</td>
    </tr>
    {% endfor %}
    </tbody>
</table>	