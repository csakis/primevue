<template>
    <DocComponent title="Vue Textarea Component" header="Textarea" description="Textarea adds styling, key filtering and autoResize functionality to standard textarea element." :componentDocs="docs" :apiDocs="['Textarea']" />
</template>

<script>
import AccessibilityDoc from '@/doc/textarea/AccessibilityDoc';
import AutoResizeDoc from '@/doc/textarea/AutoResizeDoc';
import BasicDoc from '@/doc/textarea/BasicDoc';
import DisabledDoc from '@/doc/textarea/DisabledDoc';
import FloatLabelDoc from '@/doc/textarea/FloatLabelDoc';
import ImportDoc from '@/doc/textarea/ImportDoc';
import InvalidDoc from '@/doc/textarea/InvalidDoc';
import StyleDoc from '@/doc/textarea/StyleDoc';

export default {
    data() {
        return {
            docs: [
                {
                    id: 'import',
                    label: 'Import',
                    component: ImportDoc
                },
                {
                    id: 'basic',
                    label: 'Basic',
                    component: BasicDoc
                },
                {
                    id: 'auto-resize',
                    label: 'Auto Resize',
                    component: AutoResizeDoc
                },
                {
                    id: 'float-label',
                    label: 'Float Label',
                    component: FloatLabelDoc
                },
                {
                    id: 'invalid',
                    label: 'Invalid',
                    component: InvalidDoc
                },
                {
                    id: 'disabled',
                    label: 'Disabled',
                    component: DisabledDoc
                },
                {
                    id: 'style',
                    label: 'Style',
                    component: StyleDoc
                },
                {
                    id: 'accessibility',
                    label: 'Accessibility',
                    component: AccessibilityDoc
                }
            ]
        };
    }
};
</script>
