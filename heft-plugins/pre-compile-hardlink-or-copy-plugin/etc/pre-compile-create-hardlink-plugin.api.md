## API Report File for "@rushstack/pre-compile-create-hardlink-plugin"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { HeftConfiguration } from '@rushstack/heft';
import { HeftSession } from '@rushstack/heft';
import { IHeftPlugin } from '@rushstack/heft';

// @public (undocumented)
const _default: PreCompileCreateHardlinkPlugin;

export default _default;

// @public (undocumented)
export interface IPreCompileCreateHardlinkPluginOptions {
    // (undocumented)
    linkPath: string;
    // (undocumented)
    linkTarget: string;
}

// @public (undocumented)
export class PreCompileCreateHardlinkPlugin implements IHeftPlugin<IPreCompileCreateHardlinkPluginOptions> {
    // (undocumented)
    apply(heftSession: HeftSession, heftConfiguration: HeftConfiguration, options?: IPreCompileCreateHardlinkPluginOptions): void;
    // (undocumented)
    readonly displayName: string;
    }


// (No @packageDocumentation comment for this package)

```
