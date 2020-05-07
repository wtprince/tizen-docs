# Current Xamarin.Forms Limitations

<style>
<<<<<<< HEAD
body a.squared-button {
  margin: 5px 20px 5px 0;
  display: block;
  font-size: 1.2em;
  line-height: 1.2em;
  text-transform: uppercase;
  text-align: center;
  background: #623580 url(media/white_right.png);
  background-repeat: no-repeat;
  background-position: right 10px bottom 13px;
  padding: 12px 35px 8px 12px;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  -moz-background-clip: padding;
  -webkit-background-clip: padding-box;
  background-clip: padding-box;
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  -moz-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  color: white !important;
  text-shadow: 1px 1px 1px #666;
  float: left;
  width: 14rem;
  cursor: pointer;
}
body a.squared-button:hover {
  background-color: #7c8890;
  text-decoration: none;
}
body a.squared-button-reverse {
  margin: 5px 20px 5px 0;
  display: block;
  font-size: 1.2em;
  line-height: 1.2em;
  text-transform: uppercase;
  text-align: center;
  background: #7c8890 url(media/white_right.png);
  background-repeat: no-repeat;
  background-position: right 10px bottom 13px;
  padding: 12px 35px 8px 12px;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  -moz-background-clip: padding;
  -webkit-background-clip: padding-box;
  background-clip: padding-box;
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  -moz-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.25);
  color: white !important;
  text-shadow: 1px 1px 1px #666;
  float: left;
  width: 14rem;
  cursor: pointer;
}
body a.squared-button-reverse:hover {
  background-color: #623580;
  text-decoration: none;
}

.tabcontent {
  display: none;
  clear: both;
=======
.tabcontent {
    display: none;
    clear: both;
}
.squared-button {
  width: 8rem;
}
.squared-button-reverse {
  width: 8rem;
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
}
.tdclass {
  vertical-align: top;
}
.tdtype {
  vertical-align: top;
}
<<<<<<< HEAD

body th, td {
  padding: 1px;
}
</style>

<script>
function openCity(evt, profile) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("squared-button");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className += "-reverse";
    }
    document.getElementById(profile).style.display = "block";
    evt.currentTarget.className = "squared-button";
}
</script>
=======
</style>

>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

The following table lists the classes that are supported with minor limitations. With continuous development, Tizen .NET's support for the Xamarin.Forms APIs will increase.

<a class="squared-button" onclick="return openCity(event, 'Mobile')">Mobile</a><a class="squared-button-reverse" onclick="return openCity(event, 'TV')">TV</a><a class="squared-button-reverse" onclick="return openCity(event, 'Wearable')">Wearable</a>

<div id="Mobile" class="tabcontent" style="display: block">
<table>
<<<<<<< HEAD
    <thead>
        <tr>
            <th>
                Class
            </th>
            <th>
                Type
            </th>
            <th>
                Name
            </th>
            <th>
                Remarks
            </th>
            <th colspan="1">
                Result when the feature is used
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="tdclass" rowspan="7">
                <code class="prettyprint">BoxView</code>
            </td>
            <td class="tdtype" rowspan="5"> Property
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                <code class="prettyprint">BackgroundColor</code> is ignored, use <code class="prettyprint">Color</code>.
=======
    <tbody>
        <tr>
            <th>
                <p><strong>Class</strong>
                </p>
            </th>
            <th>
                <p><strong>Type</strong>
                </p>
            </th>
            <th>
                <p><strong>Name</strong>
                </p>
            </th>
            <th>
                <p><strong>Remarks</strong>
                </p>
            </th>
            <th colspan="1">
                <p><strong>Result when the feature is used</strong>
                </p>
            </th>
        </tr>
        <tr>
            <td class="tdclass" rowspan="7">
                <p><code class="prettyprint"><span class="typ">BoxView</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="5">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code> is ignored, use <code class="prettyprint"><span class="typ">Color</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsEnabled</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                <code class="prettyprint">BoxView</code> is not interactive, and enabling does not change that.
=======
                <p><code class="prettyprint"><span class="typ">IsEnabled</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><code class="prettyprint"><span class="typ">BoxView</span></code> is not interactive, and enabling does not change that.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsFocused</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Always <code class="prettyprint">false</code>.
=======
                <p><code class="prettyprint"><span class="typ">IsFocused</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Always <code class="prettyprint"><span class="typ">false</span></code>.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Focus</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Focus</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocus</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Unfocus</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Focused</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Never triggered.
=======
                <p><span>Event</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Focused</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Never triggered.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocused</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Never triggered.
=======
                <p><code class="prettyprint"><span class="typ">Unfocused</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Never triggered.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="4">
<<<<<<< HEAD
                <code class="prettyprint">Button</code>
            </td>
            <td class="tdtype" rowspan="4">
                Property
            </td>
            <td>
                <code class="prettyprint">BorderColor</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Button</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="4">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BorderColor</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">BorderRadius</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">BorderRadius</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">BorderWidth</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">ContentLayout</code></td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">CarouselPage</code>
            </td>
            <td colspan="1">Class
            </td>
            <td colspan="1"><code class="prettyprint">CarouselPage</code>
            </td>
            <td colspan="1">Obsolete in Xamarin.Forms.</td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">BorderWidth</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">ContentLayout</span></code></td>
            <td colspan="1"></td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">CarouselPage</span></code>
            </td>
            <td colspan="1">Class
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">CarouselPage</span></code>
            </td>
            <td colspan="1">Obsolete in Xamarin.Forms.</td>
            <td colspan="1">
                <p>Does not always work as expected.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">Device</code>
            </td>
            <td class="tdtype" rowspan="2">
                Method
            </td>
            <td>
                <code class="prettyprint">OnPlatform&lt;T&gt;(T,T,T)</code>
            </td>
            <td>
                Use <code class="prettyprint">OnPlatform&lt;T&gt; (T,T,T,T)</code> instead.
            </td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">Device</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="2">
                <p>Method</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt;(T,T,T)</span></code>
                </p>
            </td>
            <td>
                <p>Use <code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt; (T,T,T,T)</span></code> instead.</p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">OnPlatform(Action, Action, Action, Action)</code>
            </td>
            <td>
                Use <code class="prettyprint">OnPlatform(Action, Action, Action, Action, Action)</code> instead.
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">EntryCell</code>
            </td>
            <td colspan="1">Property
            </td>
            <td colspan="1"><code class="prettyprint">Height</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Frame</code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint">CornerRadius</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">ImageSource</code>
            </td>
            <td colspan="1">Method</td>
            <td colspan="1"><code class="prettyprint">FromResource(string resource, Assembly sourceAssembly = null)</code>
            </td>
            <td colspan="1">sourceAssembly should be specified.</td>
            <td colspan="1">
                System.TypeInitializationException will be thrown when sourceAssembly is not to set.
=======
                <p><code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action)</span></code>
                </p>
            </td>
            <td>
                <p>Use <code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action, Action)</span></code> instead.</p>
            </td>
            <td colspan="1">
                <p>No action.
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">EntryCell</span></code>
            </td>
            <td colspan="1"><span>Property</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Height</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Frame</span></code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">CornerRadius</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">ImageSource</span></code>
            </td>
            <td colspan="1">Method</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">FromResource(string resource, Assembly sourceAssembly = null)</span></code>
            </td>
            <td colspan="1">sourceAssembly should be specified.</td>
            <td colspan="1">
                <p>System.TypeInitializationException will be thrown when sourceAssembly is not to set.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Layout</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">IsClippedToBounds</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Layout</span></code>
                </p>
            </td>
            <td>
                <p>Property
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">IsClippedToBounds</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="10">
<<<<<<< HEAD
                <code class="prettyprint">ListView</code>
            </td>
            <td class="tdtype" rowspan="7">
                Property
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td></td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">ListView</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="7">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
                </p>
            </td>
            <td></td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsPullToRefreshEnabled</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Property is always set to <code class="prettyprint">false</code>. Attempts to change it to <code class="prettyprint">true</code> are ignored.
=======
                <p><code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Property is always set to <code class="prettyprint"><span class="typ">false</span></code>. Attempts to change it to <code class="prettyprint"><span class="typ">true</span></code> are ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsRefreshing</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Always <code class="prettyprint">false</code>.
=======
                <p><code class="prettyprint"><span class="typ">IsRefreshing</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Always <code class="prettyprint"><span class="typ">false</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorColor</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Separator is not visible, so the color has no effect.
=======
                <p><code class="prettyprint"><span class="typ">SeparatorColor</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Separator is not visible, so the color has no effect.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorVisibility</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">RowHeight</code>
            </td>
            <td colspan="1">
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">RefreshCommand</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">SeparatorVisibility</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Ignored.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">RowHeight</span></code>
            </td>
            <td colspan="1">
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td colspan="1">
                <p>Does not always work as expected.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">RefreshCommand</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Method
            </td>
            <td>
                <code class="prettyprint">BeginRefresh()</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                No action.
=======
                <p>Method</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BeginRefresh()</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">EndRefresh()</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">EndRefresh()</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Refreshing</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                As <code class="prettyprint">IsPullToRefreshEnabled</code> is not supported, this event is never triggered.
=======
                <p><span>Event</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Refreshing</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>As <code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code> is not supported, this event is never triggered.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">MasterDetailPage</code>
            </td>
            <td>
                Method
            </td>
            <td>
                <code class="prettyprint">ShouldShowToolbarButton()</code>
            </td>
            <td></td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">MasterDetailPage</span></code>
                </p>
            </td>
            <td>
                <p>Method</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">ShouldShowToolbarButton()</span></code>
                </p>
            </td>
            <td></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Property
            </td>
            <td>
                <code class="prettyprint">IsGestureEnabled</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">ToolbarItems</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Only <code class="prettyprint">ToolbarItems</code> for the <code class="prettyprint">MasterDetailPage</code> are shown.
                <code class="prettyprint">ToolbarItems</code> for the <code class="prettyprint">Master</code> and <code class="prettyprint">Detail</code> pages are not shown.
=======
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">IsGestureEnabled</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">ToolbarItems</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Only <code class="prettyprint"><span class="typ">ToolbarItems</span></code> for the <code class="prettyprint"><span class="typ">MasterDetailPage</span></code> are shown.</p>
                <p><code class="prettyprint"><span class="typ">ToolbarItems</span></code> for the <code class="prettyprint"><span class="typ">Master</span></code> and <code class="prettyprint"><span class="typ">Detail</span></code> pages are not shown.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="4">
<<<<<<< HEAD
                <code class="prettyprint">NavigationPage</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">Tint</code>
            </td>
            <td>
                Obsolete in Xamarin.Forms.
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="3" colspan="1">Method
            </td>
            <td colspan="1"><code class="prettyprint">SetTitleIcon()</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">NavigationPage</span></code>
                </p>
            </td>
            <td>
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Tint</span></code>
                </p>
            </td>
            <td>
                <p><span>Obsolete in Xamarin.Forms.</span>
                </p>
            </td>
            <td colspan="1">
                <p>No action.</p>
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="3" colspan="1"><span>Method</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">SetTitleIcon()</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">GetTitleIcon()</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">SetHasBackButtonTitle()</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">GetTitleIcon()</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>No action.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">SetHasBackButtonTitle()</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">Page</code>
            </td>
            <td class="tdtype" rowspan="3">
                Property
            </td>
            <td>
                <code class="prettyprint">Icon</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsBusy</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">Page</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="3">
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Icon</span></code>
                </p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>No action.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsBusy</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Does not always work as expected.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ToolbarItems</code>
            </td>
            <td>
                Only one <code class="prettyprint">ToolbarItem</code> is supported for each Order.
                    <code class="prettyprint">Primary</code> and <code class="prettyprint">Default</code> indicate the 'right' action button on the title bar.
                    <code class="prettyprint">Secondary</code> indicates the 'left' action button on the title bar.
                    Therefore, if <code class="prettyprint">Secondary</code> is used, no back button is shown.
            </td>
            <td colspan="1">
                The priority of the 'left' action button is first <code class="prettyprint">Secondary</code> and then the back button.<br>
                For example, if a toolbar item is assigned to <code class="prettyprint">Secondary</code>, the left action button is the <code class="prettyprint">Secondary</code> toolbar item.
                Only one toolbar item is supported for each order. If multiple toolbar items are specified, the first toolbar item is used.
=======
                <p><code class="prettyprint"><span class="typ">ToolbarItems</span></code>
                </p>
            </td>
            <td>
                <p>Only one <code class="prettyprint"><span class="typ">ToolbarItem</span></code> is supported for each Order.
                    <code class="prettyprint"><span class="typ">Primary</span></code> and <code class="prettyprint"><span class="typ">Default</span></code> indicate the 'right' action button on the title bar.
                    <code class="prettyprint"><span class="typ">Secondary</span></code> indicates the 'left' action button on the title bar.
                    Therefore, if <code class="prettyprint"><span class="typ">Secondary</span></code> is used, no back button is shown.
                </p>
            </td>
            <td colspan="1">
                <p>The priority of the 'left' action button is first <code class="prettyprint"><span class="typ">Secondary</span></code> and then the back button.
                </p>
                <p>For example, if a toolbar item is assigned to <code class="prettyprint"><span class="typ">Secondary</span></code>, the left action button is the <code class="prettyprint"><span class="typ">Secondary</span></code> toolbar item.
                Only one toolbar item is supported for each order. If multiple toolbar items are specified, the first toolbar item is used.
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Slider</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">Rotation</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">Slider</span></code></p>
            </td>
            <td>
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Rotation</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Does not always work as expected.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">SwitchCell</code>
            </td>
            <td class="tdtype" rowspan="2">
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">SwitchCell</span></code></p>
            </td>
            <td class="tdtype" rowspan="2">
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">Intent</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <code class="prettyprint"><span class="typ">Intent</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">TabbedPage</code>
            </td>
            <td>Property</td>
            <td colspan="1">
                <code class="prettyprint">BarTextColor</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <code class="prettyprint"><span class="typ">TabbedPage</span></code>
            </td>
            <td>Property</td>
            <td colspan="1">
                <code class="prettyprint"><span class="typ">BarTextColor</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">TableView</code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">Property</td>
            <td colspan="1">
                <code class="prettyprint">RowHeight</code>
            </td>
            <td colspan="1">
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.<br>
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td colspan="1">
                Does not always work as expected.
=======
                <code class="prettyprint"><span class="typ">TableView</span></code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">Property</td>
            <td colspan="1">
                <code class="prettyprint"><span class="typ">RowHeight</span></code>
            </td>
            <td colspan="1">
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Does not always work as expected.
=======
                <code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Does not always work as expected.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">TextCell</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">TextCell</span></code></p>
            </td>
            <td>
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ViewCell</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">View</code>
            </td>
            <td>
            </td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">ViewCell</span></code></p>
            </td>
            <td>
                <p>Property</p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">View</span></code></p>
            </td>
            <td>
                <p></p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">WebView</code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">
                Property
            </td>
            <td colspan="1">
                <code class="prettyprint">Opacity</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <code class="prettyprint"><span class="typ">WebView</span></code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">
                <span>Property</span>
            </td>
            <td colspan="1">
                <code class="prettyprint"><span class="typ">Opacity</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
=======
                <code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p>Ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
    </tbody>
</table>
</div>

<<<<<<< HEAD
<div id="TV" class="tabcontent" style="display: none">
<table>
    <thead>
        <tr>
            <th>
                Class
            </th>
            <th>
                Type
            </th>
            <th>
                Name
            </th>
            <th>
                Remarks
            </th>
            <th colspan="1">
                Result when the feature is used
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="tdclass" rowspan="7">
                <code class="prettyprint">BoxView</code>
            </td>
            <td class="tdtype" rowspan="5">
                Property
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td>
            </td><td>
                <code class="prettyprint">BackgroundColor</code> is ignored, use <code class="prettyprint">Color</code>.
=======
<div id="TV" class="tabcontent" style="display:none">
<table>
    <tbody>
        <tr>
            <th>
                <p><span><strong>Class</strong></span></p>
            </th>
            <th>
                <p><span><strong>Type</strong></span></p>
            </th>
            <th>
                <p><span><strong>Name</strong></span></p>
            </th>
            <th>
                <p><span><strong>Remarks</strong></span></p>
            </th>
            <th colspan="1">
                <p><span><strong>Result when the feature is used</strong></span></p>
            </th>
        </tr>
        <tr>
            <td class="tdclass" rowspan="7">
                <p><code class="prettyprint"><span class="typ">BoxView</span></code></p>
            </td>
            <td class="tdtype" rowspan="5">
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code></p>
            </td>
            <td>
            </td><td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code> is ignored, use <code class="prettyprint"><span class="typ">Color</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsEnabled</code>
            </td>
            <td>
            </td><td>
                <code class="prettyprint">BoxView</code> is not interactive, and enabling does not change that.
=======
                <p><code class="prettyprint"><span class="typ">IsEnabled</span></code></p>
            </td>
            <td>
            </td><td>
                <p><code class="prettyprint"><span class="typ">BoxView</span></code> is not interactive, and enabling does not change that.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsFocused</code>
            </td>
            <td>
            </td><td>
                Always <code class="prettyprint">false</code>.
=======
                <p><code class="prettyprint"><span class="typ">IsFocused</span></code></p>
            </td>
            <td>
            </td><td>
                <p>Always <code class="prettyprint"><span class="typ">false</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Focus</code>
            </td>
            <td>
            </td><td>
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Focus</span></code></p>
            </td>
            <td>
            </td><td>
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocus</code>
            </td>
            <td>
            </td><td>
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Unfocus</span></code></p>
            </td>
            <td>
            </td><td>
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Focused</code>
            </td>
            <td>
            </td><td>
                Never triggered.
=======
                <p><span>Event</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Focused</span></code></p>
            </td>
            <td>
            </td><td>
                <p><span>Never triggered.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocused</code>
            </td>
            <td>
            </td><td>
                Never triggered.
=======
                <p><code class="prettyprint"><span class="typ">Unfocused</span></code></p>
            </td>
            <td>
            </td><td>
                <p><span>Never triggered.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="4">
<<<<<<< HEAD
                <code class="prettyprint">Button</code>
            </td>
            <td class="tdtype" rowspan="4">
                Property
            </td>
            <td>
                <code class="prettyprint">BorderColor</code>
            </td>
            <td>
            </td><td>
                Ignored.
            </td>
        </tr>
        <tr><td>
                <code class="prettyprint">BorderRadius</code>
=======
                <p><code class="prettyprint"><span class="typ">Button</span></code></p>
            </td>
            <td class="tdtype" rowspan="4">
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BorderColor</span></code></p>
            </td>
            <td>
            </td><td>
                <p>Ignored.</p>
            </td>
        </tr>
        <tr><td>
                <p><code class="prettyprint"><span class="typ">BorderRadius</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
=======
                <span>Ignored.</span>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">BorderWidth</code>
=======
                <p><code class="prettyprint"><span class="typ">BorderWidth</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">ContentLayout</code></td>
            <td>
            </td><td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">CarouselPage</code></td>
            <td>Class</td>
            <td><code class="prettyprint">CarouselPage</code></td>
            <td>Obsolete in Xamarin.Forms.</td>
            <td>
                Does not always work as expected.
=======
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">ContentLayout</span></code></td>
            <td>
            </td><td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">CarouselPage</span></code></td>
            <td><span>Class</span></td>
            <td><code class="prettyprint"><span class="typ">CarouselPage</span></code></td>
            <td><span>Obsolete in Xamarin.Forms.</span></td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">Device</code>
            </td>
            <td class="tdtype" rowspan="2">
                Method
            </td>
            <td>
                <code class="prettyprint">OnPlatform&lt;T&gt;(T,T,T)</code>
            </td>
            <td>
                Use <code class="prettyprint">OnPlatform&lt;T&gt; (T,T,T,T)</code> instead.
            </td>
            <td>
                No action.
=======
                <p><code class="prettyprint"><span class="typ">Device</span></code></p>
            </td>
            <td class="tdtype" rowspan="2">
                <p><span>Method</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt;(T,T,T)</span></code></p>
            </td>
            <td>
                <p>Use <code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt; (T,T,T,T)</span></code> instead.</p>
            </td>
            <td>
                <p><span>No action.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">OnPlatform(Action, Action, Action, Action)</code>
            </td>
            <td>
                Use <code class="prettyprint">OnPlatform(Action, Action, Action, Action, Action)</code> instead.
            </td>
            <td>
                No action.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3"><code class="prettyprint">EntryCell</code></td>
            <td>Class</td>
            <td><code class="prettyprint">EntryCell</code></td>
            <td>Mouse pointer is required for enabling user interaction on entry of the cell.</td>
            <td>
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">Property</td>
            <td><code class="prettyprint">Height</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">Keyboard</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">Frame</code></td>
            <td>Property</td>
            <td><code class="prettyprint">CornerRadius</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">ImageSource</code></td>
            <td>Method</td>
            <td><code class="prettyprint">FromResource(string resource, Assembly sourceAssembly = null)</code></td>
            <td>sourceAssembly should be specified.</td>
            <td>
                System.TypeInitializationException will be thrown when sourceAssembly is not to set.
=======
                <p><code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action)</span></code></p>
            </td>
            <td>
                <p>Use <code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action, Action)</span></code> instead.</p>
            </td>
            <td>
                <p><span>No action.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3"><code class="prettyprint"><span class="typ">EntryCell</span></code></td>
            <td><span>Class</span></td>
            <td><code class="prettyprint"><span class="typ">EntryCell</span></code></td>
            <td><span>Mouse pointer is required for enabling user interaction on entry of the cell.</span></td>
            <td>
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2"><span>Property</span></td>
            <td><code class="prettyprint"><span class="typ">Height</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p>Ignored.</p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">Keyboard</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">Frame</span></code></td>
            <td>Property</td>
            <td><code class="prettyprint"><span class="typ">CornerRadius</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">ImageSource</span></code></td>
            <td><span>Method</span></td>
            <td><code class="prettyprint"><span class="typ">FromResource(string resource, Assembly sourceAssembly = null)</span></code></td>
            <td><span>sourceAssembly should be specified.</span></td>
            <td>
                <p><span>System.TypeInitializationException will be thrown when sourceAssembly is not to set.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Layout</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">IsClippedToBounds</code>
=======
                <p><code class="prettyprint"><span class="typ">Layout</span></code></p>
            </td>
            <td>
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">IsClippedToBounds</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
=======
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="10">
<<<<<<< HEAD
                <code class="prettyprint">ListView</code>
            </td>
            <td class="tdtype" rowspan="7">
                Property
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">ListView</span></code></p>
            </td>
            <td class="tdtype" rowspan="7">
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code></p>
            </td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsPullToRefreshEnabled</code>
=======
                <p><code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Property is always set to <code class="prettyprint">false</code>. Attempts to change it to <code class="prettyprint">true</code> are ignored.
=======
                <p>Property is always set to <code class="prettyprint"><span class="typ">false</span></code>. Attempts to change it to <code class="prettyprint"><span class="typ">true</span></code> are ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsRefreshing</code>
=======
                <p><code class="prettyprint"><span class="typ">IsRefreshing</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Always <code class="prettyprint">false</code>.
=======
                <p>Always <code class="prettyprint"><span class="typ">false</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorColor</code>
=======
                <p><code class="prettyprint"><span class="typ">SeparatorColor</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
=======
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorVisibility</code>
=======
                <p><code class="prettyprint"><span class="typ">SeparatorVisibility</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">RowHeight</code></td>
            <td>
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td>
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">RefreshCommand</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
=======
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">RowHeight</span></code></td>
            <td>
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td>
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">RefreshCommand</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Method
            </td>
            <td>
                <code class="prettyprint">BeginRefresh()</code>
=======
                <p><span>Method</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BeginRefresh()</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                No action.
=======
                <p><span>No action.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">EndRefresh()</code>
=======
                <p><code class="prettyprint"><span class="typ">EndRefresh()</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                No action.
=======
                <p><span>No action.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Refreshing</code>
=======
                <p><span>Event</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Refreshing</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                As <code class="prettyprint">IsPullToRefreshEnabled</code> is not supported, this event is never triggered.
=======
                <p>As <code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code> is not supported, this event is never triggered.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">MasterDetailPage</code>
            </td>
            <td>
                Method
            </td>
            <td>
                <code class="prettyprint">ShouldShowToolbarButton()</code>
            </td>
            <td>&nbsp;</td>
            <td>
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">MasterDetailPage</span></code></p>
            </td>
            <td>
                <p><span>Method</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">ShouldShowToolbarButton()</span></code></p>
            </td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Property
            </td>
            <td>
                <code class="prettyprint">IsGestureEnabled</code>
=======
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">IsGestureEnabled</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                <div>Does not always work as expected.</div>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">ToolbarItems</code></td>
            <td>&nbsp;</td>
            <td>
                Only <code class="prettyprint">ToolbarItems</code> for the <code class="prettyprint">MasterDetailPage</code> are shown.
                <code class="prettyprint">ToolbarItems</code> for the <code class="prettyprint">Master</code> and <code class="prettyprint">Detail</code> pages are not shown.
=======
                <div><span>Does not always work as expected.</span></div>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">ToolbarItems</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p>Only <code class="prettyprint"><span class="typ">ToolbarItems</span></code> for the <code class="prettyprint"><span class="typ">MasterDetailPage</span></code> are shown.
                <code class="prettyprint"><span class="typ">ToolbarItems</span></code> for the <code class="prettyprint"><span class="typ">Master</span></code> and <code class="prettyprint"><span class="typ">Detail</span></code> pages are not shown.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="5">
<<<<<<< HEAD
                <code class="prettyprint">NavigationPage</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">Tint</code>
            </td>
            <td>
                Obsolete in Xamarin.Forms.
            </td>
            <td>
                No action.
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="4">Method</td>
            <td><code class="prettyprint">SetTitleIcon()</code></td>
            <td>&nbsp;</td>
            <td>
                No action.
=======
                <p><code class="prettyprint"><span class="typ">NavigationPage</span></code></p>
            </td>
            <td>
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Tint</span></code></p>
            </td>
            <td>
                <p><span>Obsolete in Xamarin.Forms.</span></p>
            </td>
            <td>
                <p><span>No action.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="4"><span>Method</span></td>
            <td><code class="prettyprint"><span class="typ">SetTitleIcon()</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>No action.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">GetTitleIcon()</code>
=======
                <p><code class="prettyprint"><span class="typ">GetTitleIcon()</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                No action.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">SetHasBackButton()</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">SetHasBackButtonTitle()</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">PinchGestureRecognizer</code></td>
            <td>Event</td>
            <td><code class="prettyprint">PinchUpdated</code></td>
            <td>&nbsp;</td>
            <td>
                Never occured.
=======
                <p><span>No action.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">SetHasBackButton()</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">SetHasBackButtonTitle()</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">PinchGestureRecognizer</span></code></td>
            <td><span>Event</span></td>
            <td><code class="prettyprint"><span class="typ">PinchUpdated</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Never occured.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">Page</code>
            </td>
            <td class="tdtype" rowspan="3">
                Property
            </td>
            <td>
                <code class="prettyprint">Icon</code>
=======
                <p><code class="prettyprint"><span class="typ">Page</span></code></p>
            </td>
            <td class="tdtype" rowspan="3">
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Icon</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                No action.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">IsBusy</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
=======
                <p><span>No action.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">IsBusy</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ToolbarItems</code>
=======
                <p><code class="prettyprint"><span class="typ">ToolbarItems</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">SearchBar</code></td>
            <td>Class</td>
            <td><code class="prettyprint">SearchBar</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
=======
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">SearchBar</span></code></td>
            <td><span>Class</span></td>
            <td><code class="prettyprint"><span class="typ">SearchBar</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Slider</code>
            </td>
            <td>Property</td>
            <td><code class="prettyprint">BackgroundColor</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2"><code class="prettyprint">Stepper</code></td>
            <td>
                Class
            </td>
            <td><code class="prettyprint">Stepper</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always shown as expected.
            </td>
        </tr>
        <tr>
            <td>Property</td>
            <td><code class="prettyprint">BackgroundColor</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3"><code class="prettyprint">SwitchCell</code></td>
            <td>Class</td>
            <td><code class="prettyprint">SwitchCell</code></td>
            <td>Mouse pointer is required for enabling user interaction on switch of the cell.</td>
            <td>
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">Slider</span></code></p>
            </td>
            <td><span>Property</span></td>
            <td><code class="prettyprint"><span class="typ">BackgroundColor</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2"><code class="prettyprint"><span class="typ">Stepper</span></code></td>
            <td>
                <p><span>Class</span></p>
            </td>
            <td><code class="prettyprint"><span class="typ">Stepper</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always shown as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td><span>Property</span></td>
            <td><code class="prettyprint"><span class="typ">BackgroundColor</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3"><code class="prettyprint"><span class="typ">SwitchCell</span></code></td>
            <td><span>Class</span></td>
            <td><code class="prettyprint"><span class="typ">SwitchCell</span></code></td>
            <td><span>Mouse pointer is required for enabling user interaction on switch of the cell.</span></td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
=======
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">Intent</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">TabbedPage</code></td>
            <td>Property</td>
            <td><code class="prettyprint">BarTextColor</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2"><code class="prettyprint">TableView</code></td>
            <td class="tdtype" rowspan="2">Property</td>
            <td><code class="prettyprint">RowHeight</code></td>
            <td>
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td>
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">BackgroundColor</code></td>
            <td>&nbsp;</td>
            <td>
                Does not always work as expected.
=======
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">Intent</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">TabbedPage</span></code></td>
            <td><span>Property</span></td>
            <td><code class="prettyprint"><span class="typ">BarTextColor</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2"><code class="prettyprint"><span class="typ">TableView</span></code></td>
            <td class="tdtype" rowspan="2"><span>Property</span></td>
            <td><code class="prettyprint"><span class="typ">RowHeight</span></code></td>
            <td>
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td>
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">BackgroundColor</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Does not always work as expected.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">TextCell</code>
            </td>
            <td class="tdtype" rowspan="2">
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
=======
                <p><code class="prettyprint"><span class="typ">TextCell</span></code></p>
            </td>
            <td class="tdtype" rowspan="2">
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Ignored.
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint">Detail</code></td>
            <td>&nbsp;</td>
            <td>
                Ignored.
=======
                <div><span>Ignored.</span></div>
            </td>
        </tr>
        <tr>
            <td><code class="prettyprint"><span class="typ">Detail</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Ignored.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ViewCell</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">View</code>
=======
                <p><code class="prettyprint"><span class="typ">ViewCell</span></code></p>
            </td>
            <td>
                <p><span>Property</span></p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">View</span></code></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
            <td>
            </td>
            <td>
<<<<<<< HEAD
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td class="tdclass"><code class="prettyprint">WebView</code></td>
            <td class="tdtype">Class</td>
            <td><code class="prettyprint">WebView</code></td>
            <td>&nbsp;</td>
            <td>
                Application will fail to launch.
=======
                <p><span>Does not always work as expected.</span></p>
            </td>
        </tr>
        <tr>
            <td class="tdclass"><code class="prettyprint"><span class="typ">WebView</span></code></td>
            <td class="tdtype"><span>Class</span></td>
            <td><code class="prettyprint"><span class="typ">WebView</span></code></td>
            <td>&nbsp;</td>
            <td>
                <p><span>Application will fail to launch.</span></p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
    </tbody>
</table>
</div>

<<<<<<< HEAD
<div id="Wearable" class="tabcontent" style="display: none">
<table>
    <thead>
        <tr>
            <th>
                Class
            </th>
            <th>
                Type
            </th>
            <th>
                Name
            </th>
            <th>
                Remarks
            </th>
            <th colspan="1">
                Result when the feature is used
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="tdclass" rowspan="6" colspan="1"><code class="prettyprint">ActivityIndicator</code>
            </td>
            <td class="tdtype" rowspan="6" colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint">Opacity</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">HeightRequest</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">WidthRequest</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsEnabled</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsRunning</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                ignored.
=======
<div id="Wearable" class="tabcontent" style="display:none">
<table>
    <tbody>
        <tr>
            <th>
                <p><span><strong>Class</strong></span>
                </p>
            </th>
            <th>
                <p><span><strong>Type</strong></span>
                </p>
            </th>
            <th>
                <p><span><strong>Name</strong></span>
                </p>
            </th>
            <th>
                <p><span><strong>Remarks</strong></span>
                </p>
            </th>
            <th colspan="1">
                <p><span><strong>Result when the feature is used</strong></span>
                </p>
            </th>
        </tr>
        <tr>
            <td class="tdclass" rowspan="6" colspan="1"><code class="prettyprint"><span class="typ">ActivityIndicator</span></code>
            </td>
            <td class="tdtype" rowspan="6" colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Opacity</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>Does not always work as expected</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">HeightRequest</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>Does not always work as expected</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">WidthRequest</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>Does not always work as expected</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsEnabled</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>ignored.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsRunning</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>Does not always work as expected</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>ignored.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="7">
<<<<<<< HEAD
                <code class="prettyprint">BoxView</code>
            </td>
            <td class="tdtype" rowspan="5">
                Property
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                <code class="prettyprint">BackgroundColor</code>&nbsp;is ignored, use&nbsp;<code class="prettyprint">Color</code>.
=======
                <p><code class="prettyprint"><span class="typ">BoxView</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="5">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code>&nbsp;is ignored, use&nbsp;<code class="prettyprint"><span class="typ">Color</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsEnabled</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                <code class="prettyprint">BoxView</code>&nbsp;is not interactive, and enabling does not change that.
=======
                <p><code class="prettyprint"><span class="typ">IsEnabled</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><code class="prettyprint"><span class="typ">BoxView</span></code>&nbsp;is not interactive, and enabling does not change that.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsFocused</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Always&nbsp;<code class="prettyprint">false</code>.
=======
                <p><code class="prettyprint"><span class="typ">IsFocused</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p>Always&nbsp;<code class="prettyprint"><span class="typ">false</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Focus</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Focus</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocus</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Unfocus</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Focused</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Never triggered.
=======
                <p><span>Event</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Focused</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Never triggered.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Unfocused</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Never triggered.
=======
                <p><code class="prettyprint"><span class="typ">Unfocused</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Never triggered.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="5">
<<<<<<< HEAD
                <code class="prettyprint">Button</code>
            </td>
            <td class="tdtype" rowspan="5">
                Property
            </td>
            <td>
                <code class="prettyprint">BorderColor</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                <div>Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Button</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="5">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BorderColor</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <div><span>Ignored.</span>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
                </div>
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">BorderRadius</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                <div>Ignored.
=======
                <p><code class="prettyprint"><span class="typ">BorderRadius</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <div><span>Ignored.</span>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
                </div>
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">BorderWidth</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">ContentLayout</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Opacity</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">CarouselPage</code>
            </td>
            <td colspan="1">Class
            </td>
            <td colspan="1"><code class="prettyprint">CarouselPage</code>
            </td>
            <td colspan="1">Obsolete in Xamarin.Forms.
            </td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">BorderWidth</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">ContentLayout</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Opacity</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">CarouselPage</span></code>
            </td>
            <td colspan="1"><span>Class</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">CarouselPage</span></code>
            </td>
            <td colspan="1"><span>Obsolete in Xamarin.Forms.</span>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">Device</code>
            </td>
            <td class="tdtype" rowspan="2">
                Method
            </td>
            <td>
                <code class="prettyprint">OnPlatform&lt;T&gt;(T,T,T)</code>
            </td>
            <td>
                &nbsp;Use <code class="prettyprint">OnPlatform&lt;T&gt; (T,T,T,T)</code> instead.
            </td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">Device</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="2">
                <p><span>Method</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt;(T,T,T)</span></code></p>
            </td>
            <td>
                <p><span>&nbsp;Use <code class="prettyprint"><span class="typ">OnPlatform&lt;T&gt; (T,T,T,T)</span></code> instead.</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">OnPlatform(Action, Action, Action, Action)</code>
            </td>
            <td>
                &nbsp;Use <code class="prettyprint">OnPlatform(Action, Action, Action, Action, Action)</code> instead.
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">DatePicker</code>
            </td>
            <td colspan="1">Class
            </td>
            <td colspan="1"><code class="prettyprint">DatePicker</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Not Supported.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Editor</code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint">Editor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Entry</code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint">Entry</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint">EntryCell</code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">Property
            </td>
            <td colspan="1"><code class="prettyprint">Height</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Keyboard</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Frame</code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint">CornerRadius</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Image</code>
            </td>
            <td colspan="1">Property
            </td>
            <td colspan="1"><code class="prettyprint">IsOpaque</code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">ImageSource</code>
            </td>
            <td colspan="1">Method
            </td>
            <td colspan="1"><code class="prettyprint">FromResource(string resource, Assembly sourceAssembly = null)</code>
            </td>
            <td colspan="1">sourceAssembly should be specified.
            </td>
            <td colspan="1">
                System.TypeInitializationException will be thrown when sourceAssembly is not to set.
=======
                <p><code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action)</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;Use <code class="prettyprint"><span class="typ">OnPlatform(Action, Action, Action, Action, Action)</span></code> instead.</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">DatePicker</span></code>
            </td>
            <td colspan="1"><span>Class</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">DatePicker</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Not Supported.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Editor</span></code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Editor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Entry</span></code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Entry</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint"><span class="typ">EntryCell</span></code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1"><span>Property</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Height</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p>Ignored.</p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Keyboard</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span><span>Does not always work as expected.</span></span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Frame</span></code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">CornerRadius</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Image</span></code>
            </td>
            <td colspan="1"><span>Property</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsOpaque</span></code>
            </td>
            <td colspan="1"></td>
            <td colspan="1">
                <p><span>Ignored.</span></p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">ImageSource</span></code>
            </td>
            <td colspan="1"><span>Method</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">FromResource(string resource, Assembly sourceAssembly = null)</span></code>
            </td>
            <td colspan="1"><span>sourceAssembly should be specified.</span>
            </td>
            <td colspan="1">
                <p><span>System.TypeInitializationException will be thrown when sourceAssembly is not to set.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">Layout</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">IsClippedToBounds</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span>Layout</span></code>
                </p>
            </td>
            <td>
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span>IsClippedToBounds</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="10">
<<<<<<< HEAD
                <code class="prettyprint">ListView</code>
            </td>
            <td class="tdtype" rowspan="7">
                Property&nbsp;
            </td>
            <td>
                <code class="prettyprint">BackgroundColor</code>
            </td>
            <td>&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">ListView</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="7">
                <p><span>Property&nbsp;</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
                </p>
            </td>
            <td>&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsPullToRefreshEnabled</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Property is always set to&nbsp;<code class="prettyprint">false</code>. Attempts to change it to&nbsp;<code class="prettyprint">true</code>&nbsp;are ignored.
=======
                <p><code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Property is always set to&nbsp;<code class="prettyprint"><span class="typ">false</span></code>. Attempts to change it to&nbsp;<code class="prettyprint"><span class="typ">true</span></code>&nbsp;are ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">IsRefreshing</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Always&nbsp;<code class="prettyprint">false</code>.
=======
                <p><code class="prettyprint"><span class="typ">IsRefreshing</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p>Always&nbsp;<code class="prettyprint"><span class="typ">false</span></code>.</p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorColor</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Separator is not visible, so the color has no effect.
=======
                <p><code class="prettyprint"><span class="typ">SeparatorColor</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Separator is not visible, so the color has no effect.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">SeparatorVisibility</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">RowHeight</code>
            </td>
            <td colspan="1">
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">RefreshCommand</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">SeparatorVisibility</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">RowHeight</span></code>
            </td>
            <td colspan="1">
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">RefreshCommand</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="2">
<<<<<<< HEAD
                Method
            </td>
            <td>
                <code class="prettyprint">BeginRefresh()</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                No action.
=======
                <p><span>Method</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">BeginRefresh()</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">EndRefresh()</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">EndRefresh()</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                Event
            </td>
            <td>
                <code class="prettyprint">Refreshing</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                As&nbsp;<code class="prettyprint">IsPullToRefreshEnabled</code>&nbsp;is not supported, this event is never triggered.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">MasterDetailPage</code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint">MasterDetailPage</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Not Supported.
=======
                <p><span>Event</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Refreshing</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p>As&nbsp;<code class="prettyprint"><span class="typ">IsPullToRefreshEnabled</span></code>&nbsp;is not supported, this event is never triggered.
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">MasterDetailPage</span></code>
            </td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">MasterDetailPage</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Not Supported.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="5">
<<<<<<< HEAD
                <code class="prettyprint">NavigationPage</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">Tint</code>
            </td>
            <td>
                Obsolete in Xamarin.Forms.
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="4" colspan="1">Method
            </td>
            <td colspan="1"><code class="prettyprint">SetTitleIcon()</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                No action.
=======
                <p><code class="prettyprint"><span class="typ">NavigationPage</span></code>
                </p>
            </td>
            <td>
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Tint</span></code>
                </p>
            </td>
            <td>
                <p><span>Obsolete in Xamarin.Forms.</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td class="tdtype" rowspan="4" colspan="1"><span>Method</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">SetTitleIcon()</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">GetTitleIcon()</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">SetHasBackButton()</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.&nbsp;
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">SetHasBackButtonTitle()</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.&nbsp;
=======
                <p><code class="prettyprint"><span class="typ">GetTitleIcon()</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">SetHasBackButton()</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.&nbsp;</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">SetHasBackButtonTitle()</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.&nbsp;</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">Page</code>
            </td>
            <td class="tdtype" rowspan="3">
                Property
            </td>
            <td>
                <code class="prettyprint">Icon</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                No action.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsBusy</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">Page</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="3">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Icon</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>No action.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsBusy</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ToolbarItems</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Picker</code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint">Opacity</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">SearchBar</code></td>
            <td colspan="1">Class
            </td>
            <td colspan="1"><code class="prettyprint">SearchBar</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">ToolbarItems</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span><span>Does not always work as expected.</span></span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Picker</span></code>
            </td>
            <td colspan="1">Property</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Opacity</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">SearchBar</span></code></td>
            <td colspan="1"><span>Class</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">SearchBar</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td colspan="1">
<<<<<<< HEAD
                <code class="prettyprint">Slider</code>
            </td>
            <td colspan="1">
                Property
            </td><td colspan="1"><code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Stepper</code></td>
            <td colspan="1">Property&nbsp;
            </td>
            <td colspan="1"><code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">Slider</span></code></p>
            </td>
            <td colspan="1">
                <p><span>Property</span></p>
            </td><td colspan="1"><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Stepper</span></code></td>
            <td colspan="1"><span>Property&nbsp;</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2">
<<<<<<< HEAD
                <code class="prettyprint">SwitchCell</code>
            </td>
            <td class="tdtype" rowspan="2">
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">Intent</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint">TabbedPage</code></td>
            <td class="tdtype" rowspan="2" colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint">TabbedPage</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Not Supported.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">BarTextColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3" colspan="1"><code class="prettyprint">TableView</code></td>
            <td class="tdtype" rowspan="3" colspan="1">Property
            </td>
            <td colspan="1"><code class="prettyprint">RowHeight</code></td>
            <td colspan="1">
                This is applied when <code class="prettyprint">HasUnevenRows</code> is set to <code class="prettyprint">true</code>.
                However, <code class="prettyprint">RowHeight</code> value may not be affected to Cells due to the policy of Tizen platform.
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsEnabled</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
=======
                <p><code class="prettyprint"><span class="typ">SwitchCell</span></code></p>
            </td>
            <td class="tdtype" rowspan="2">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code>
                </p>
            </td>
            <td>
                <p>&nbsp;</p>
            </td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">Intent</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint"><span class="typ">TabbedPage</span></code></td>
            <td class="tdtype" rowspan="2" colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">TabbedPage</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Not Supported.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">BarTextColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3" colspan="1"><code class="prettyprint"><span class="typ">TableView</span></code></td>
            <td class="tdtype" rowspan="3" colspan="1"><span>Property</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">RowHeight</span></code></td>
            <td colspan="1">
                <p>This is applied when <code class="prettyprint"><span class="typ">HasUnevenRows</span></code> is set to <code class="prettyprint"><span class="typ">true</span></code>.</p>
                <p>However, <code class="prettyprint"><span class="typ">RowHeight</span></code> value may not be affected to Cells due to the policy of Tizen platform.</p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span><span>Does not always work as expected.</span></span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsEnabled</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span><span>Does not always work as expected.</span></span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="3">
<<<<<<< HEAD
                <code class="prettyprint">TextCell</code>
            </td>
            <td class="tdtype" rowspan="3">
                Property
            </td>
            <td>
                <code class="prettyprint">Height</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                <div>Ignored.
=======
                <p><code class="prettyprint"><span class="typ">TextCell</span></code>
                </p>
            </td>
            <td class="tdtype" rowspan="3">
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">Height</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <div><span>Ignored.</span>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
                </div>
            </td>
        </tr>
        <tr>
<<<<<<< HEAD
            <td colspan="1"><code class="prettyprint">Detail</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">IsEnabled</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">TimePicker</code></td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint">TimePicker</code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Not Supported.
=======
            <td colspan="1"><code class="prettyprint"><span class="typ">Detail</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">IsEnabled</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">TimePicker</span></code></td>
            <td colspan="1">Class</td>
            <td colspan="1"><code class="prettyprint"><span class="typ">TimePicker</span></code></td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Not Supported.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
        <tr>
            <td>
<<<<<<< HEAD
                <code class="prettyprint">ViewCell</code>
            </td>
            <td>
                Property
            </td>
            <td>
                <code class="prettyprint">View</code>
            </td>
            <td>
                &nbsp;
            </td>
            <td colspan="1">
                Does not always work as expected.
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint">WebView</code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1">Property
            </td>
            <td colspan="1"><code class="prettyprint">Opacity</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint">BackgroundColor</code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                Ignored.
=======
                <p><code class="prettyprint"><span class="typ">ViewCell</span></code>
                </p>
            </td>
            <td>
                <p><span>Property</span>
                </p>
            </td>
            <td>
                <p><code class="prettyprint"><span class="typ">View</span></code>
                </p>
            </td>
            <td>
                <p><span>&nbsp;</span>
                </p>
            </td>
            <td colspan="1">
                <p><span>Does not always work as expected.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td class="tdclass" rowspan="2" colspan="1"><code class="prettyprint"><span class="typ">WebView</span></code>
            </td>
            <td class="tdtype" rowspan="2" colspan="1"><span>Property</span>
            </td>
            <td colspan="1"><code class="prettyprint"><span class="typ">Opacity</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="1"><code class="prettyprint"><span class="typ">BackgroundColor</span></code>
            </td>
            <td colspan="1">&nbsp;</td>
            <td colspan="1">
                <p><span>Ignored.</span>
                </p>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
            </td>
        </tr>
    </tbody>
</table>
</div>
<<<<<<< HEAD
=======

<script>
function openCity(evt, profile) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("squared-button");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className += "-reverse";
    }
    document.getElementById(profile).style.display = "block";
    evt.currentTarget.className = "squared-button";
}
</script>
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
