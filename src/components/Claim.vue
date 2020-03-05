<template>
    <div class="claimWrapper">
        <h1 class="claim">NASA API
            <p class="subclaim">
                Begin your jurney through our amazing galxy,
                 and discover places you never ecen heard of.
            </p>
            <p class="subclaim">
                Type anthing NASA-API to start.
            </p>
        </h1>
    </div>
</template>
<script>
export default {
  name: 'Claim',
};
</script>
<style lang="scss" scoped>
    .claimWrapper {
        display: flex;
        text-align: center;
        flex-direction: column;
        justify-conntent: center;
        algin-items: center;
    };

    .claim {
        font-size: 50px;
        margin : 0;
        color: white;

        @media (min-width: 768px) {
            font-size: 80px;
        }
    }

    .subclaim {
        matgin: 20px 0 0 0;
        width: 500px;
        font-size: 20px;
        font-weight: 400;

        @media (min-width: 768px) {
            font-size: 17px;
            line-height: 1;
            letter-spacing: 1px;
        }
    }
</style>
