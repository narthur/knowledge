# PHP

## Snippets

`array_map_recursive` \([source](https://stackoverflow.com/a/39637749/937377)\):

```php
function array_map_recursive($callback, $array)
{
  $func = function ($item) use (&$func, &$callback) {
    return is_array($item) ? array_map($func, $item) : call_user_func($callback, $item);
  };

  return array_map($func, $array);
}
```

## PHPStorm

[Mastering PhpStorm keyboard shortcuts](https://www.jetbrains.com/help/phpstorm/mastering-keyboard-shortcuts.html) \#article - "PhpStorm has keyboard shortcuts for most of its commands related to editing, navigation, refactoring, debugging, and other tasks. Memorizing these hotkeys can help you stay more productive by keeping your hands on the keyboard."

<table>
  <thead>
    <tr>
      <th style="text-align:left">Shortcut</th>
      <th style="text-align:left">Action</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Double Ctrl</td>
      <td style="text-align:left">
        <p>Run Anything</p>
        <p>Execute commands, such as opening a project, launching a run/debug configuration,
          running a command-line utility, and so on. The available commands depend
          on the set of plugins and tools you have configured for your project.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Double Shift</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/searching-everywhere.html">Search Everywhere</a>
        </p>
        <p>Find anything related to PhpStorm or your project and open it, execute
          it, or jump to it.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x21E7;&#x2318;A</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/searching-everywhere.html#find_action">Find Action</a>
        </p>
        <p>Find a command and execute it, open a tool window or search for a setting.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2318;O
        <br />&#x21E7;&#x2318;O
        <br />&#x2325;&#x2318;O</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/searching-everywhere.html">Find a class, file, or symbol</a>
        </p>
        <p>Find and jump to the desired class, file, or symbol.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2318;E</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/navigating-through-the-source-code.html#recent_files">View recent files</a>
        </p>
        <p>Select a recently opened file from the list.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2325;&#x23CE;</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/intention-actions.html">Show intention actions</a>
        </p>
        <p>Improve or optimize a code construct.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2303;Space</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/auto-completing-code.html#basic_completion">Basic code completion</a>
        </p>
        <p>Complete names of classes, methods, fields, and keywords within the visibility
          scope.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2325;&#x2191;
        <br />&#x2325;&#x2193;</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/working-with-source-code.html">Extend or shrink selection</a>
        </p>
        <p>Increase or decrease the scope of selection according to specific code
          constructs.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2318;/
        <br />&#x2325;&#x2318;/</td>
      <td style="text-align:left">
        <p><a href="https://www.jetbrains.com/help/phpstorm/working-with-source-code.html#editor_lines_code_blocks">Add/remove line or block comment</a>
        </p>
        <p>Comment out a line or block of code.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x21E7;&#x2318;F7</td>
      <td style="text-align:left">
        <p>Highlight usages in a file</p>
        <p>Highlight all occurrences of the selected fragment in the current file.</p>
      </td>
    </tr>
  </tbody>
</table>