<template>
    <div>
        <table class="first-padding">
            <tr>
                <td><b>Account</b></td>
                <td><public-key :value="operation.account"></public-key></td>
            </tr>
            <tr>
                <td><b>Into</b></td>
                <td><public-key :value="operation.into"></public-key></td>
            </tr>
        </table>
    </div>
</template>

<script>
  export default {
    props: ['operation']
  }
</script>