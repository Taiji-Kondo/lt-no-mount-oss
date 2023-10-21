---
layout: default
---

<table class="text-sm">
    <caption>OSSライセンスざっくりまとめ</caption>
    <thead>
        <tr class="bg-gray-800">
            <th>レベル</th>
            <th>ライセンス例</th>
            <th>ライセンス等の表示<span class="text-xs">※1</span></th>
            <th>利用者へのコード公開<span class="text-xs">※2</span></th>
            <th>利用物のコード公開<span class="text-xs">※3</span></th>
            <th>改造物のコード公開<span class="text-xs">※4</span></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>超危険</td>
            <td>
                <ul class="mt-0!">
                    <li>AGPL</li>
                </ul>
            </td>
            <td class="text-red-500">必要</td>
            <td class="text-red-500">必要</td>
            <td class="text-red-500">必要</td>
            <td class="text-red-500">必要</td>
        </tr>
        <tr>
            <td>危険</td>
            <td>
                <ul class="mt-0!">
                    <li>GPL</li>
                </ul>
            </td>
            <td class="text-red-500">必要</td>
            <td>不要</td>
            <td class="text-red-500">必要</td>
            <td class="text-red-500">必要</td>
        </tr>
        <tr>
            <td>注意</td>
            <td>
                <ul class="mt-0!">
                    <li>LGPL</li>
                    <li>MPL</li>
                </ul>
            </td>
            <td class="text-red-500">必要</td>
            <td>不要</td>
            <td>不要</td>
            <td class="text-red-500">必要</td>
        </tr>
        <tr>
            <td>安心</td>
            <td>
                <ul class="mt-0!">
                    <li>Apache License</li>
                    <li>PostgreSQL License</li>
                    <li>BSD License</li>
                    <li>MIT</li>
                </ul>
            </td>
            <td class="text-red-500">必要</td>
            <td>不要</td>
            <td>不要</td>
            <td>不要</td>
        </tr>
    </tbody>
</table>

<div class="text-xs mt-10">※1 主に再配布時に明記する必要がある、インターネット経由での配信では不要なことが多い</div>
<div class="text-xs">※2 インターネット経由で配信した際に利用者にソースコードを開示する必要があるか</div>
<div class="text-xs">※3 再配布時にソースコードを開示する必要があるか</div>
<div class="text-xs">※4 対象ライセンスを持つOSSを改良して再配布した場合にソースコードを開示する必要があるか</div>
