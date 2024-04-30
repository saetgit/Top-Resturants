import type { NuxtLayout } from '#build/components';
import { RestaurantTable } from '#build/components';

import type { RestaurantRow } from '#build/components';
<template>
    <div>
        <NuxtLayout name="custome">
            <div class="container">
                <RestaurantTable />
            </div>
        </NuxtLayout>
    </div>
</template>