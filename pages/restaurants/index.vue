import type { NuxtLayout } from '#build/components';
import { RestaurantTable } from '#build/components';

import type { RestaurantRow } from '#build/components';
<template>
    <div>
        <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">

        <Head>
            <Title>Top 5O Restaurants in the World</Title>
            <Meta name="description" content="My page is cool" />
            <Link rel="preload" href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
                as="script" />
        </Head>

        </Html>
        <NuxtLayout name="custome">
            <div class="container">
                <RestaurantTable />
            </div>
        </NuxtLayout>
    </div>
</template>