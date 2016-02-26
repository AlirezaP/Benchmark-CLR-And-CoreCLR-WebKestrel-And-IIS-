# Benchmark-CLR-And-CoreCLR-WebKestrel-And-IIS-
LoadTest on CLR AND CORECLR With iis and web Kestrel.<br/>

This test done in my personal PC (OS: Win10)<br/>

This is Not Exact But is good For Approximate knowledge.<br/>

<table align="center" border="1" width="1000" style="text-align:center">
    <tr>
        <td>

        </td>
        <td>CoreCLR Web Kestrel (In Debug environment)</td>
        <td>.NetFramework Web Kestrel (In Debug environment)</td>
        <td>IIS dnx-Coreclr-win-x64.1.0.0-rc1-update1</td>
        <td>IIS dnx-clr-win-x64.1.0.0-rc1-update1</td>
    </tr>

    <tr>
        <td>Pages/Sec</td>
        <td>1.66</td>
        <td>1.25</td>
        <td>1.44</td>
        <td>1.05</td>
    </tr>

    <tr>
        <td>Avg. Page Time (sec)</td>
        <td>55.3</td>
        <td>35.8</td>
        <td>61.4</td>
        <td>73.2</td>
    </tr>

    <tr>
        <td>Requests/Sec</td>
        <td>11.2</td>
        <td>10.1</td>
        <td>9.06</td>
        <td>6.69</td>
    </tr>

    <tr>
        <td>Avg. Response Time (sec)</td>
        <td>26.6</td>
        <td>20.9</td>
        <td>33.7</td>
        <td>41.1</td>
    </tr>
</table>
<br/>


