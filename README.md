# List of standard lengths for database fields

Description here

<table>
    <tr>
        <th>Field</th>
        <th>MsSQL</th>
        <th>MySQL</th>
        <th>Length</th>
        <th>Reason</th>
    </tr>
    <tr>
        <td>Email address</td>
        <td>
            nvarchar
        </td>
        <td>
            varchar
        </td>
        <td>254</td>
        <td>see RFC5321</td>
    </tr>
    <tr>
        <td>City</td>
        <td>
            nvarchar
        </td>
        <td>
            varchar
        </td>
        <td>254</td>
        <td>Longest City Name is located in Bangkok, Thailand: Krung Thep Mahanakhon Amon Rattanakosin Mahinthara Ayuthaya Mahadilok Phop Noppharat Ratchathani Burirom Udomratchaniwet Mahasathan Amon Piman Awatan Sathit Sakkathattiya Witsanukam Prasit</td>
    </tr>
    <tr>
        <td>Zip code</td>
        <td>
            nvarchar
        </td>
        <td>
            varchar
        </td>
        <td>18</td>
        <td>Country with the longest zip code format is Chile with NNNNNNN, NNN-NNNN</td>
    </tr>
    <tr>
        <td>Country</td>
        <td>
            nvarchar
        </td>
        <td>
            varchar
        </td>
        <td>90</td>
        <td>Longest country name is Libya’s Arabic name prior to 2013: al-Jam-h-riyyah al-‘Arabiyyah al-L?biyyah ash-Sha‘biyyah al-Ishtir-kiyyah al-‘U-má</td>
    </tr>
</table>
